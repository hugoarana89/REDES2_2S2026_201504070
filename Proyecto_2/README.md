 <div align="center">

<img src="https://commons.wikimedia.org/wiki/Special:FilePath/Usac_logo.png" alt="Logo de la Universidad de San Carlos de Guatemala" width="120" />


  # Proyecto Conectividad XXI

  ### Integración de Operadores Nacionales

  **Universidad de San Carlos de Guatemala**  
  Facultad de Ingeniería · Ingeniería en Sistemas

  <br />

  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&duration=3500&pause=900&color=2563EB&center=true&vCenter=true&width=650&lines=Redes+de+Computadoras+2;Proyecto+2" alt="Redes de Computadoras 2 - Proyecto 2" />

  **Segundo semestre de 2026**

  <br />

  ![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
  ![Curso](https://img.shields.io/badge/Curso-Redes%202-0b5394?style=flat-square)
  ![Semestre](https://img.shields.io/badge/Sección-A-6aa84f?style=flat-square)

</div>

---

## Información académica

| Campo | Información |
|:--|:--|
| **Estudiante** | Hugo Jorge Luis Pérez Arana |
| **Registro académico** | 201504070 |
| **Catedrático** | Ing. Allan Alberto Morataya Gómez |
| **Auxiliar** | Dominic Juan Pablo Ruano Pérez |
| **Sección** | N |

---

## Descripción del proyecto

El proyecto consiste en diseñar e implementar una infraestructura nacional de telecomunicaciones que interconecte tres o cuatro proveedores de servicio (ISP). Cada ISP tiene requisitos específicos de topología, protocolos de enrutamiento interno (OSPF, EIGRP, RIP) y servicios críticos. La interconexión entre ISPs se realiza mediante BGP utilizando la red 192.168.X.0/16.

---

## Subneteo y plan de direccionamiento

### Variables derivadas del carné

Con el carné **201504070** se obtienen los siguientes valores:

| Variable | Regla del enunciado | Valor |
|:--|:--|:--|
| `XX` | Últimos 2 dígitos del carné | `70` |
| `X` (FibraNet y AndinaCom) | Último dígito del carné | `0` |
| `X` (MoonLink) | Primer dígito del carné | `2` |

### Redes asignadas

| Red | Uso | Dirección asignada |
|:--|:--|:--|
| ISP 1 | FibraNet GT | `172.16.10.0/24` |
| ISP 2 | AndinaCom | `172.16.20.0/24` |
| ISP 3 | MoonLink | `172.16.32.0/24` |
| Interconexión | Enlaces entre routers y switches multicapa | `192.168.70.0/24` (bloque de trabajo) |

---

### ISP 1: FibraNet GT (`172.16.10.0/24`)

Cada departamento debe soportar hasta **75 hosts**. Con 7 bits de host se obtienen 2⁷ − 2 = 126 direcciones utilizables, por lo que se requiere una máscara **/25** (`255.255.255.128`). Con 6 bits solo se obtendrían 62, insuficientes.

| Departamento | Red | Máscara | Rango utilizable | Broadcast | Hosts | Gateway |
|:--|:--|:--|:--|:--|:--:|:--|
| Administración | `172.16.10.0/25` | `255.255.255.128` | `.1` – `.126` | `.127` | 126 | `172.16.10.1` |
| Atención al Cliente | `172.16.10.128/25` | `255.255.255.128` | `.129` – `.254` | `.255` | 126 | `172.16.10.129` |

**Servidor DNS y HTTP/HTTPS:** se ubica dentro de la subred de Administración, con dirección estática reservada fuera del rango de DHCP.

| Elemento | Dirección |
|:--|:--|
| Rango reservado para infraestructura y servidores (excluido de DHCP) | `172.16.10.110` – `172.16.10.126` |
| Servidor DNS / HTTP / HTTPS | `172.16.10.125` |

---

### ISP 2: AndinaCom (`172.16.20.0/24`)

El tamaño de las subredes es libre. Se utilizan subredes /26 para los departamentos (62 hosts utilizables cada una), una subred /27 para el servidor DHCP y un bloque /26 reservado para enlaces punto a punto. La topología jerárquica con HSRP requiere en cada subred una dirección virtual y dos direcciones reales (una por cada switch multicapa de distribución).

| Subred | Red | Máscara | Rango utilizable | Broadcast | HSRP virtual | Real (Dist-1 / Dist-2) |
|:--|:--|:--|:--|:--|:--|:--|
| Ventas | `172.16.20.0/26` | `255.255.255.192` | `.1` – `.62` | `.63` | `172.16.20.1` | `.2` / `.3` |
| Facturación | `172.16.20.64/26` | `255.255.255.192` | `.65` – `.126` | `.127` | `172.16.20.65` | `.66` / `.67` |
| Servidores (DHCP) | `172.16.20.128/27` | `255.255.255.224` | `.129` – `.158` | `.159` | `172.16.20.129` | `.130` / `.131` |
| Reserva | `172.16.20.160/27` | `255.255.255.224` | `.161` – `.190` | `.191` | — | — |
| Enlaces punto a punto | `172.16.20.192/26` | `255.255.255.192` | Subdividido en /30 | `.255` | — | — |

| Elemento | Dirección |
|:--|:--|
| Servidor DHCP centralizado | `172.16.20.132` |

Enlaces punto a punto (/30) disponibles dentro de `172.16.20.192/26`:

| Enlace | Red | Hosts utilizables |
|:--|:--|:--|
| Enlace 1 | `172.16.20.192/30` | `.193` – `.194` |
| Enlace 2 | `172.16.20.196/30` | `.197` – `.198` |
| Enlace 3 | `172.16.20.200/30` | `.201` – `.202` |
| Enlace 4 | `172.16.20.204/30` | `.205` – `.206` |
| Enlace 5 | `172.16.20.208/30` | `.209` – `.210` |
| Enlace 6 | `172.16.20.212/30` | `.213` – `.214` |

Los 10 bloques /30 restantes (`172.16.20.216/30` hasta `172.16.20.252/30`) quedan libres.

---

### ISP 3: MoonLink (`172.16.32.0/24`)

Cada departamento debe soportar hasta **45 hosts**. Con 6 bits de host se obtienen 2⁶ − 2 = 62 direcciones utilizables, por lo que se requiere una máscara **/26** (`255.255.255.192`). Con 5 bits solo se obtendrían 30, insuficientes.

| Subred | Red | Máscara | Rango utilizable | Broadcast | Hosts | Gateway |
|:--|:--|:--|:--|:--|:--:|:--|
| Soporte | `172.16.32.0/26` | `255.255.255.192` | `.1` – `.62` | `.63` | 62 | `172.16.32.1` |
| Seguridad | `172.16.32.64/26` | `255.255.255.192` | `.65` – `.126` | `.127` | 62 | `172.16.32.65` |
| Red inalámbrica (reservada) | `172.16.32.128/26` | `255.255.255.192` | `.129` – `.190` | `.191` | 62 | `172.16.32.129` |
| Enlaces punto a punto | `172.16.32.192/26` | `255.255.255.192` | Subdividido en /30 | `.255` | — | — |

Enlaces punto a punto (/30) para la topología hub-and-spoke dentro de `172.16.32.192/26`:

| Enlace | Red | Hosts utilizables |
|:--|:--|:--|
| Hub – Spoke 1 | `172.16.32.192/30` | `.193` – `.194` |
| Hub – Spoke 2 | `172.16.32.196/30` | `.197` – `.198` |
| Hub – Spoke 3 | `172.16.32.200/30` | `.201` – `.202` |
| Hub – Spoke 4 | `172.16.32.204/30` | `.205` – `.206` |

Los 12 bloques /30 restantes (`172.16.32.208/30` hasta `172.16.32.252/30`) quedan libres.

---

### Red de interconexión (`192.168.70.0`)

#### Enlaces BGP entre los switches multicapa de borde

Cada enlace punto a punto utiliza una máscara **/30** (`255.255.255.252`), que ofrece exactamente 2 direcciones utilizables y evita el desperdicio de direcciones.

| Enlace | Red | Extremo A | Extremo B |
|:--|:--|:--|:--|
| FibraNet GT – AndinaCom | `192.168.70.0/30` | `192.168.70.1` (FibraNet) | `192.168.70.2` (AndinaCom) |
| AndinaCom – MoonLink | `192.168.70.4/30` | `192.168.70.5` (AndinaCom) | `192.168.70.6` (MoonLink) |
| FibraNet GT – MoonLink | `192.168.70.8/30` | `192.168.70.9` (FibraNet) | `192.168.70.10` (MoonLink) |
| Reserva | `192.168.70.12/30` | — | — |

El conjunto completo de enlaces BGP se resume en `192.168.70.0/28`.

#### Enlaces internos de FibraNet GT

| Bloque | Red | Uso |
|:--|:--|:--|
| Enlaces internos FibraNet | `192.168.70.16/27` | Ocho subredes /30: `.16`, `.20`, `.24`, `.28`, `.32`, `.36`, `.40`, `.44` |
| Libre | `192.168.70.48/28` en adelante | Reserva para crecimiento |

---

### Resumen general

| ISP | Red asignada | Subredes de usuario | Máscara | Protocolo interno | Topología |
|:--|:--|:--|:--:|:--|:--|
| FibraNet GT | `172.16.10.0/24` | Administración, Atención al Cliente | /25 | OSPF | Árbol |
| AndinaCom | `172.16.20.0/24` | Ventas, Facturación | /26 | OSPF | Jerárquica (HSRP) |
| MoonLink | `172.16.32.0/24` | Soporte, Seguridad | /26 | EIGRP | Hub-and-spoke |

---

### Decisiones de diseño

1. **Interpretación de `192.168.XX.0/16`.** La dirección `192.168.70.0` con máscara /16 no es una dirección de red válida, ya que la red correspondiente sería `192.168.0.0/16`. Se tomó `192.168.70.0/24` como bloque de trabajo y se subdividió en subredes /30, con lo que se garantiza un subneteo eficiente.
2. **Enlaces internos de FibraNet GT.** Las dos subredes /25 consumen la totalidad de `172.16.10.0/24`, sin direcciones disponibles para los enlaces entre routers. El enunciado indica que la red `192.168.XX.0` se asigna para conectar routers y switches de capa 3, por lo que los enlaces internos de este ISP se tomaron de `192.168.70.16/27`. Así se respeta el requisito de 75 hosts por departamento sin utilizar direccionamiento ajeno al enunciado.
3. **Ubicación del servidor DNS/HTTP.** Dado que FibraNet GT no dispone de una subred adicional, el servidor se ubica en la subred de Administración. Este departamento mantiene comunicación bidireccional con cualquier otro, de modo que las reglas de la tabla 4.2 no afectan el acceso al servicio.
4. **Subred de servidores en AndinaCom.** Se separó el servidor DHCP en una subred propia (`172.16.20.128/27`) protegida por HSRP, para que el servicio no dependa de un único gateway.
5. **Red inalámbrica en MoonLink.** Se reservó una subred /26 para el router inalámbrico. El departamento al que pertenecerán los clientes inalámbricos queda pendiente de definir.

### Consideraciones para fases posteriores

- Las ACLs deben permitir explícitamente el tráfico de DNS (UDP/53) y de DHCP (UDP/67 y UDP/68) hacia los servidores, ya que la tabla 4.2 solo menciona ICMP, TCP/80 y TCP/443. De lo contrario, la resolución de nombres y la asignación de direcciones fallarían entre ISPs.
- Los routers y switches multicapa que sirvan de gateway en FibraNet GT y MoonLink requieren `ip helper-address` apuntando a `172.16.20.132` para que los hosts obtengan direccionamiento desde el servidor DHCP de AndinaCom.