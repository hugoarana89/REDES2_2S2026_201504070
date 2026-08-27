#### Universidad de San Carlos de Guatemala
#### Facultad de Ingeniería
#### Escuela de Ciencias y Sistemas
#### Inteligencia artificial 1
#### Ing. Allan Alberto Morataya Gómez
#### Aux. Dominic Juan Pablo Ruano Perez
#### Sección A
<br><br><br><br><br><br><br>
<p style="text-align: center;"><strong> Proyecto <br> Chapin Red <br>
</strong></p>
<br><br><br><br><br><br><br>

| Nombre                                    | Carnet    |
| :---:                                     |  :----:   |
| HUGO JORGE LUIS PÉREZ ARANA               | 201504070 |


## Capturas de la topología completa

<div align="center">
  <img src="img/Topologia_completa.jpg" alt="" width="100%">
</div>

## Topología etiquetando los tipos de interfaces y medios de transmisión.

<div align="center">
  <img src="img/Topologia_etiquetas.jpg" alt="" width="100%">
</div>

## Topología etiquetando puertos.

<div align="center">
  <img src="img/Topologia_puertos.jpg" alt="" width="100%">
</div>


## Conexiones

| Dispositivo Origen | Puerto Origen | Dispositivo Destino | Puerto Destino | Nota |
|---|---|---|---|---|
| 3650-24PS (MS1) | Gig1/0/1 | Server-PT (DHCP1) | Fa0 |  |
| 3650-24PS (MS1) | Gig1/0/2 | Server-PT (DHCP2) | Fa0 |  |
| 3650-24PS (MS1) | Gig1/1/1 | 3650-24PS (MS2) | Gig1/1/1 | Fibra óptica |
| 3650-24PS (MS1) | Gig1/1/2 | 3650-24PS (MS7) | Gig1/1/2 | Fibra óptica |
| 3650-24PS (MS2) | Gig1/1/2 | 3650-24PS (MS6) | Gig1/1/2 | Fibra óptica |
| 3650-24PS (MS2) | Gig1/1/3 | 3650-24PS (MS7) | Gig1/1/3 | Fibra óptica |
| 3650-24PS (MS6) | Gig1/1/1 | 3650-24PS (MS7) | Gig1/1/1 | Fibra óptica |
| 3650-24PS (MS2) | Gig1/0/1 | 3650-24PS (MS3) | Gig1/0/1 | |
| 3650-24PS (MS2) | Gig1/0/2 | 3650-24PS (MS3) | Gig1/0/2 | |
| 3650-24PS (MS2) | Gig1/0/3 | 3650-24PS (MS3) | Gig1/0/3 | |
| 3650-24PS (MS3) | Gig1/0/4 | 3650-24PS (MS4) | Gig1/0/1 | |
| 3650-24PS (MS3) | Gig1/0/5 | 3650-24PS (MS4) | Gig1/0/2 | |
| 3650-24PS (MS3) | Gig1/0/6 | 3650-24PS (MS4) | Gig1/0/3 | |
| 3650-24PS (MS3) | Gig1/0/7 | 3650-24PS (MS4) | Gig1/0/4 | |
| 3650-24PS (MS4) | Gig1/0/5 | 3650-24PS (MS5) | Gig1/0/1 | |
| 3650-24PS (MS5) | Gig1/0/2 | 2960-24TT (SW3) | Fa0/1 | |
| 3650-24PS (MS5) | Gig1/0/3 | 2960-24TT (SW4) | Fa0/1 | |
| 2960-24TT (SW3) | Fa0/2 | Laptop-PT (Laptop2) | Fa0 | |
| 2960-24TT (SW3) | Fa0/3 | PC-PT (PC3) | Fa0 | |
| 2960-24TT (SW4) | Fa0/2 | Laptop-PT (Laptop3) | Fa0 | |
| 2960-24TT (SW4) | Fa0/3 | PC-PT (PC4) | Fa0 | |
| 3650-24PS (MS9) | Gig1/0/1 | 3650-24PS (MS8) | Gig1/0/1 | |
| 3650-24PS (MS9) | Gig1/0/2 | 3650-24PS (MS8) | Gig1/0/2 | |
| 3650-24PS (MS9) | Gig1/0/3 | 3650-24PS (MS8) | Gig1/0/3 | |
| 3650-24PS (MS7) | Gig1/0/1 | 3650-24PS (MS8) | Gig1/0/4 | |
| 3650-24PS (MS7) | Gig1/0/2 | 3650-24PS (MS8) | Gig1/0/5 | |
| 3650-24PS (MS7) | Gig1/0/3 | 3650-24PS (MS8) | Gig1/0/6 | |
| 3650-24PS (MS7) | Gig1/0/4 | 3650-24PS (MS9) | Gig1/0/4 | |
| 3650-24PS (MS7) | Gig1/0/5 | 3650-24PS (MS9) | Gig1/0/5 | |
| 3650-24PS (MS7) | Gig1/0/6 | 3650-24PS (MS9) | Gig1/0/6 | |
| 3650-24PS (MS9) | Gig1/0/7 | 2960-24TT (SW1) | Fa0/1 | |
| 3650-24PS (MS9) | Gig1/0/8 | 2960-24TT (SW1) | Fa0/2 | |
| 3650-24PS (MS8) | Gig1/0/7 | 2960-24TT (SW2) | Fa0/1 | |
| 3650-24PS (MS8) | Gig1/0/8 | 2960-24TT (SW2) | Fa0/2 | |
| 2960-24TT (SW1) | Fa0/3 | PC-PT (PC1) | Fa0 | |
| 2960-24TT (SW1) | Fa0/4 | PC-PT (PC2) | Fa0 | |
| 2960-24TT (SW2) | Fa0/3 | Laptop-PT (Laptop0) | Fa0 | |
| 2960-24TT (SW2) | Fa0/4 | Laptop-PT (Laptop1) | Fa0 | |
| 3650-24PS (MS6) | Gig1/0/1 | PC-PT (PC0) | Fa0 | |

**Edificio Izquierdo**
- MS7 – MS8 (EtherChannel, 3 enlaces)
- MS7 – MS9 (EtherChannel, 3 enlaces)
- MS8 – MS9 (EtherChannel, 3 enlaces)
- MS9 – SW1, MS8 – SW2 (acceso)
- SW1 – PC1, PC2; SW2 – Laptop0, Laptop1 (acceso final)

**Edificio Derecho**
- MS2 – MS3 (EtherChannel, 3 enlaces)
- MS3 – MS4 (EtherChannel, 4 enlaces)
- MS4 – MS5, MS5 – SW3, MS5 – SW4 (acceso)
- SW3 – Laptop2, PC3; SW4 – Laptop3, PC4 (acceso final)

**Centro**
- MS1 – DHCP1, MS1 – DHCP2 (servidores)
- MS6 – PC0 (acceso final, VLAN ADMIN)


> En todos los Multilayers Switch se debe habilitar los puertos de fibra óptica, se debe entrar en la pestaña Physical y arrastrar el módulo GLC-LH-SMD ha uno de los slots vacíos.


## Cálculo de hosts y VLSM para las VLANs

### Conteo de hosts por VLAN

| VLAN | Edificio | Dispositivos | Hosts actuales |
|---|---|---|---|
| Naranja | Izquierdo | PC1, Laptop0 | 2 |
| Verde | Izquierdo | PC2, Laptop1 | 2 |
| Naranja | Derecho | PC3, PC4 | 2 |
| Verde | Derecho | Laptop2, Laptop3 | 2 |
| ADMIN | Centro | PC0 | 1 |

### Subnetting VLSM — Red `192.188.70.0/24`

| # | VLAN | Red / Prefijo | Rango de hosts | Gateway | Broadcast | Hosts útiles |
|---|---|---|---|---|---|---|
| 1 | VLAN_Naranja_EdificioIZQ_201504070 | 192.188.70.0/29 | .1 – .6 | 192.188.70.1 | 192.188.70.7 | 6 |
| 2 | VLAN_Verde_EdificioIZQ_201504070 | 192.188.70.8/29 | .9 – .14 | 192.188.70.9 | 192.188.70.15 | 6 |
| 3 | VLAN_Naranja_EdificioDER_201504070 | 192.188.70.16/29 | .17 – .22 | 192.188.70.17 | 192.188.70.23 | 6 |
| 4 | VLAN_Verde_EdificioDER_201504070 | 192.188.70.24/29 | .25 – .30 | 192.188.70.25 | 192.188.70.31 | 6 |
| 5 | VLAN_ADMIN_201504070 | 192.188.70.32/29 | .33 – .38 | 192.188.70.33 | 192.188.70.39 | 6 |

> El rango total utilizado corresponde a `192.188.70.0` – `192.188.70.39`, de las 256 direcciones disponibles en el bloque `/24`, dejando el resto libre para expansión futura. La convención de gateway asigna siempre la primera IP utilizable de cada subred a la interfaz SVI del switch multicapa correspondiente.

Falta un elemento: aún no se generó la tabla FLSM `/30` con las direcciones concretas para los 5 enlaces de Capa 3 identificados. Se completa a continuación.

### FLSM `/30` — Red `10.4.70.0/24`

| # | Enlace | Red / Prefijo | IP extremo 1 | IP extremo 2 | Broadcast |
|---|---|---|---|---|---|
| 1 | MS1 – MS2 | 10.4.70.0/30 | 10.4.70.1 (MS1) | 10.4.70.2 (MS2) | 10.4.70.3 |
| 2 | MS1 – MS7 | 10.4.70.4/30 | 10.4.70.5 (MS1) | 10.4.70.6 (MS7) | 10.4.70.7 |
| 3 | MS2 – MS6 | 10.4.70.8/30 | 10.4.70.9 (MS2) | 10.4.70.10 (MS6) | 10.4.70.11 |
| 4 | MS2 – MS7 | 10.4.70.12/30 | 10.4.70.13 (MS2) | 10.4.70.14 (MS7) | 10.4.70.15 |
| 5 | MS6 – MS7 | 10.4.70.16/30 | 10.4.70.17 (MS6) | 10.4.70.18 (MS7) | 10.4.70.19 |

El rango total utilizado corresponde a `10.4.70.0` – `10.4.70.19`, dejando el resto del bloque `/24` disponible para futuros enlaces de enrutamiento si el diseño lo requiere.

---

### Numeración y nomenclatura de VLANs

| # VLAN | Nombre (convención `VLAN_[Color]_Edificio[IZQ/DER]_[Carnet]`) | Edificio | Subred asociada |
|---|---|---|---|
| 10 | VLAN_Naranja_EdificioIZQ_201504070 | Izquierdo | 192.188.70.0/29 |
| 20 | VLAN_Verde_EdificioIZQ_201504070 | Izquierdo | 192.188.70.8/29 |
| 30 | VLAN_Naranja_EdificioDER_201504070 | Derecho | 192.188.70.16/29 |
| 40 | VLAN_Verde_EdificioDER_201504070 | Derecho | 192.188.70.24/29 |
| 99 | VLAN_ADMIN_201504070 | Centro | 192.188.70.32/29 |

---

## Configuración de hostname de dispositivos

### Edificio Izquierdo

**MS7**
```
enable
configure terminal
hostname MS7
end
write memory
exit
```

**MS8**
```
enable
configure terminal
hostname MS8
end
write memory
exit
```

**MS9**
```
enable
configure terminal
hostname MS9
end
write memory
exit
```

**SW1**
```
enable
configure terminal
hostname SW1
end
write memory
exit
```

**SW2**
```
enable
configure terminal
hostname SW2
end
write memory
exit
```

---

### Edificio Derecho

**MS2**
```
enable
configure terminal
hostname MS2
end
write memory
exit
```

**MS3**
```
enable
configure terminal
hostname MS3
end
write memory
exit
```

**MS4**
```
enable
configure terminal
hostname MS4
end
write memory
exit
```

**MS5**
```
enable
configure terminal
hostname MS5
end
write memory
exit
```

**SW3**
```
enable
configure terminal
hostname SW3
end
write memory
exit
```

**SW4**
```
enable
configure terminal
hostname SW4
end
write memory
exit
```

---

### Centro

**MS1**
```
enable
configure terminal
hostname MS1
end
write memory
exit
```

**MS6**
```
enable
configure terminal
hostname MS6
end
write memory
exit
```

---

## VTP — dominio y roles de Server/Client

### Configuración general del dominio VTP

| Parámetro | Valor propuesto |
|---|---|
| Nombre del dominio | `ChapinRed` |
| Contraseña | `ChapinRed2026` (a elección, se documenta igual) |
| Versión VTP | 2 |

### Roles por switch

| Switch | Rol VTP | Justificación |
|---|---|---|
| **MS7** (Izquierdo) | **Server** | Es el switch donde se originan/crean las VLANs 10 y 20 del edificio izquierdo; actúa como punto de distribución hacia MS8, MS9 y los switches de acceso. |
| MS8 | Client | Recibe las VLANs desde MS7, no necesita crear VLANs propias. |
| MS9 | Client | Igual que MS8. |
| SW1 (2960) | Client | Switch de acceso, solo recibe la base de datos VLAN. |
| SW2 (2960) | Client | Switch de acceso, solo recibe la base de datos VLAN. |
| **MS2** (Derecho) | **Server** | Es el switch donde se originan/crean las VLANs 30 y 40 del edificio derecho; distribuye hacia MS3, MS4, MS5 y switches de acceso. |
| MS3 | Client | Recibe VLANs desde MS2. |
| MS4 | Client | Recibe VLANs desde MS2/MS3. |
| MS5 | Client | Recibe VLANs desde MS4. |
| SW3 (2960) | Client | Switch de acceso. |
| SW4 (2960) | Client | Switch de acceso. |
| **MS6** (Centro) | **Server** | Origina la VLAN 99 (ADMIN), ya que PC0 está conectado directamente a este switch. |
| MS1 (Centro) | Client | Switch de tránsito en la malla central; no necesita originar VLANs, solo participa del dominio para mantener consistencia de la base de datos VTP. |


### Configuración de Edificio Izquierdo

**MS7 (VTP Server)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode server
vlan 10
name VLAN_Naranja_EdificioIZQ_201504070
exit
vlan 20
name VLAN_Verde_EdificioIZQ_201504070
exit
end
write memory
exit
```

**MS8 (VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

**MS9 (VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

**SW1 (2960 - VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

**SW2 (2960 - VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

---

### Configuración de Edificio Derecho

**MS2 (VTP Server)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode server
vlan 30
name VLAN_Naranja_EdificioDER_201504070
exit
vlan 40
name VLAN_Verde_EdificioDER_201504070
exit
end
write memory
exit
```

**MS3 (VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

**MS4 (VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

**MS5 (VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

**SW3 (2960 - VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

**SW4 (2960 - VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

---

### Configuración de dispositivos del Centro

**MS6 (VTP Server)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode server
vlan 99
name VLAN_ADMIN_201504070
exit
end
write memory
exit
```

**MS1 (VTP Client)**
```
enable
configure terminal
vtp domain ChapinRed
vtp password ChapinRed2026
vtp version 2
vtp mode client
end
write memory
exit
```

---

**Verificación después de aplicar todos los comandos:**
```
show vtp status
show vlan brief
```

---

## Configuración de enlaces trunk

### Enlaces que requieren trunk

| Enlace | VLANs que transporta |
|---|---|
| MS9 (Gig1/0/7, Gig1/0/8) ↔ SW1 (Fa0/1, Fa0/2) | 10, 20 |
| MS8 (Gig1/0/7, Gig1/0/8) ↔ SW2 (Fa0/1, Fa0/2) | 10, 20 |
| MS4 (Gig1/0/5) ↔ MS5 (Gig1/0/1) | 30, 40 |
| MS5 (Gig1/0/2) ↔ SW3 (Fa0/1) | 30, 40 |
| MS5 (Gig1/0/3) ↔ SW4 (Fa0/1) | 30, 40 |

---

### Edificio Izquierdo

**MS9**
```
enable
configure terminal
interface range gig1/0/7 - 8
switchport mode trunk
switchport trunk allowed vlan 10,20
end
write memory
exit
```

**MS8**
```
enable
configure terminal
interface range gig1/0/7 - 8
switchport mode trunk
switchport trunk allowed vlan 10,20
end
write memory
exit
```

**SW1**
```
enable
configure terminal
interface range fa0/1 - 2
switchport mode trunk
switchport trunk allowed vlan 10,20
end
write memory
exit
```

**SW2**
```
enable
configure terminal
interface range fa0/1 - 2
switchport mode trunk
switchport trunk allowed vlan 10,20
end
write memory
exit
```

---

### Edificio Derecho

**MS4**
```
enable
configure terminal
interface gig1/0/5
switchport mode trunk
switchport trunk allowed vlan 30,40
end
write memory
exit
```

**MS5**
```
enable
configure terminal
interface gig1/0/1
switchport mode trunk
switchport trunk allowed vlan 30,40
exit
interface gig1/0/2
switchport mode trunk
switchport trunk allowed vlan 30,40
exit
interface gig1/0/3
switchport mode trunk
switchport trunk allowed vlan 30,40
end
write memory
exit
```

**SW3**
```
enable
configure terminal
interface fa0/1
switchport mode trunk
switchport trunk allowed vlan 30,40
end
write memory
exit
```

**SW4**
```
enable
configure terminal
interface fa0/1
switchport mode trunk
switchport trunk allowed vlan 30,40
end
write memory
exit
```

### Configurar modo access a dispositivos finales

**SW1**

```
enable
configure terminal
interface fa0/3
switchport mode access
switchport access vlan 10
exit
interface fa0/4
switchport mode access
switchport access vlan 20
end
write memory
exit
```

**SW2**
```
enable
configure terminal
interface fa0/3
switchport mode access
switchport access vlan 10
exit
interface fa0/4
switchport mode access
switchport access vlan 20
end
write memory
exit
```

**SW3**
```
enable
configure terminal
interface fa0/2
switchport mode access
switchport access vlan 40
exit
interface fa0/3
switchport mode access
switchport access vlan 30
end
write memory
exit
```

**SW4**
```
enable
configure terminal
interface fa0/2
switchport mode access
switchport access vlan 40
exit
interface fa0/3
switchport mode access
switchport access vlan 30
end
write memory
exit
```


---

## Configuración de EtherChannel (LACP / PAgP)

### Resumen de agrupación — Edificio Izquierdo (LACP)

| Canal | Switches | Puertos MS7 | Puertos MS8 | Puertos MS9 | Channel-group |
|---|---|---|---|---|---|
| Po1 | MS7 ↔ MS8 | Gig1/0/1-3 | Gig1/0/4-6 | — | 1 |
| Po2 | MS7 ↔ MS9 | Gig1/0/4-6 | — | Gig1/0/4-6 | 2 |
| Po1 (en MS8/MS9) | MS8 ↔ MS9 | — | Gig1/0/1-3 | Gig1/0/1-3 | 1 |

### Comandos — MS7 (LACP, 2 canales)

```
enable
configure terminal
interface range gig1/0/1 - 3
channel-group 1 mode active
exit
interface range gig1/0/4 - 6
channel-group 2 mode active
exit
interface port-channel 1
switchport mode trunk
switchport trunk allowed vlan 10,20
exit
interface port-channel 2
switchport mode trunk
switchport trunk allowed vlan 10,20
end
write memory
exit
```

### Comandos — MS8 (LACP, 2 canales)

```
enable
configure terminal
interface range gig1/0/1 - 3
channel-group 2 mode active
exit
interface range gig1/0/4 - 6
channel-group 1 mode active
exit
interface port-channel 1
switchport mode trunk
switchport trunk allowed vlan 10,20
exit
interface port-channel 2
switchport mode trunk
switchport trunk allowed vlan 10,20
end
write memory
exit
```

### Comandos — MS9 (LACP, 2 canales)

```
enable
configure terminal
interface range gig1/0/1 - 3
channel-group 1 mode active
exit
interface range gig1/0/4 - 6
channel-group 2 mode active
exit
interface port-channel 1
switchport mode trunk
switchport trunk allowed vlan 10,20
exit
interface port-channel 2
switchport mode trunk
switchport trunk allowed vlan 10,20
end
write memory
exit
```

---

### Edificio Derecho (PAgP)


| Canal | Switches | Puertos origen | Puertos destino | Channel-group |
|---|---|---|---|---|
| Po1 | MS2 ↔ MS3 | Gig1/0/1-3 (MS2) | Gig1/0/1-3 (MS3) | 1 |
| Po2 | MS3 ↔ MS4 | Gig1/0/4-7 (MS3) | Gig1/0/1-4 (MS4) | 2 en MS3, 1 en MS4 |

### Comandos — MS2 (PAgP)

```
enable
configure terminal
interface range gig1/0/1 - 3
channel-group 1 mode desirable
exit
interface port-channel 1
switchport mode trunk
switchport trunk allowed vlan 30,40
end
write memory
exit
```

### Comandos — MS3 (PAgP, 2 canales)

```
enable
configure terminal
interface range gig1/0/1 - 3
channel-group 1 mode desirable
exit
interface range gig1/0/4 - 7
channel-group 2 mode desirable
exit
interface port-channel 1
switchport mode trunk
switchport trunk allowed vlan 30,40
exit
interface port-channel 2
switchport mode trunk
switchport trunk allowed vlan 30,40
end
write memory
exit
```

### Comandos — MS4 (PAgP)

```
enable
configure terminal
interface range gig1/0/1 - 4
channel-group 1 mode desirable
exit
interface port-channel 1
switchport mode trunk
switchport trunk allowed vlan 30,40
end
write memory
exit
```

---

**Verificación recomendada tras aplicar todo:**
```
show etherchannel summary
show etherchannel port-channel
```

---

## Configuración de Spanning Tree Protocol (STP)

Se usará **Rapid PVST+** configurando el switch núcleo de cada edificio como **Root Primary** y otro como **Root Secondary** para dar redundancia. Además, se activa **PortFast** en los puertos que conectan directamente a dispositivos finales, ya que esos puertos no necesitan pasar por los estados de escucha/aprendizaje de STP.

### Asignación de roles STP

| Edificio | VLANs | Root Primary | Root Secondary |
|---|---|---|---|
| Izquierdo | 10, 20 | MS7 | MS8 |
| Derecho | 30, 40 | MS2 | MS3 |
| Centro | 99 | MS6 | — (única VLAN, un solo switch de origen) |

---

### Edificio Izquierdo

**MS7 (Root Primary VLAN 10, 20)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
spanning-tree vlan 10,20 root primary
end
write memory
exit
```

**MS8 (Root Secondary VLAN 10, 20)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
spanning-tree vlan 10,20 root secondary
end
write memory
exit
```

**MS9**
```
enable
configure terminal
spanning-tree mode rapid-pvst
end
write memory
exit
```

**SW1 (con PortFast en puertos de acceso a PC1, PC2)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
interface range fa0/3 - 4
spanning-tree portfast
end
write memory
exit
```

**SW2 (con PortFast en puertos de acceso a Laptop0, Laptop1)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
interface range fa0/3 - 4
spanning-tree portfast
end
write memory
exit
```

---

### Edificio Derecho

**MS2 (Root Primary VLAN 30, 40)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
spanning-tree vlan 30,40 root primary
end
write memory
exit
```

**MS3 (Root Secondary VLAN 30, 40)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
spanning-tree vlan 30,40 root secondary
end
write memory
exit
```

**MS4**
```
enable
configure terminal
spanning-tree mode rapid-pvst
end
write memory
exit
```

**MS5**
```
enable
configure terminal
spanning-tree mode rapid-pvst
end
write memory
exit
```

**SW3 (con PortFast en puertos de acceso a Laptop2, PC3)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
interface range fa0/2 - 3
spanning-tree portfast
end
write memory
exit
```

**SW4 (con PortFast en puertos de acceso a Laptop3, PC4)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
interface range fa0/2 - 3
spanning-tree portfast
end
write memory
exit
```

---

### Centro

**MS6 (Root Primary VLAN 99, PortFast hacia PC0)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
spanning-tree vlan 99 root primary
interface gig1/0/1
spanning-tree portfast
end
write memory
exit
```

**MS1 (PortFast hacia los servidores DHCP)**
```
enable
configure terminal
spanning-tree mode rapid-pvst
interface range gig1/0/1 - 2
spanning-tree portfast
end
write memory
exit
```

---

**Verificación de configuración:**
```
show spanning-tree summary
show spanning-tree vlan 10
```

---

## SVIs + OSPF (inter-VLAN y entre edificios)

### Resumen de interfaces routeadas (enlaces de fibra, `10.4.70.0/24`)

| Switch | Interfaz | IP | Enlace hacia |
|---|---|---|---|
| MS1 | Gig1/1/1 | 10.4.70.1/30 | MS2 |
| MS1 | Gig1/1/2 | 10.4.70.5/30 | MS7 |
| MS2 | Gig1/1/1 | 10.4.70.2/30 | MS1 |
| MS2 | Gig1/1/2 | 10.4.70.9/30 | MS6 |
| MS2 | Gig1/1/3 | 10.4.70.13/30 | MS7 |
| MS6 | Gig1/1/1 | 10.4.70.17/30 | MS7 |
| MS6 | Gig1/1/2 | 10.4.70.10/30 | MS2 |
| MS7 | Gig1/1/1 | 10.4.70.18/30 | MS6 |
| MS7 | Gig1/1/2 | 10.4.70.6/30 | MS1 |
| MS7 | Gig1/1/3 | 10.4.70.14/30 | MS2 |

### Resumen de SVIs (gateways de VLAN, `192.188.70.0/24`)

| Switch | VLAN | SVI IP |
|---|---|---|
| MS7 | 10 | 192.188.70.1/29 |
| MS7 | 20 | 192.188.70.9/29 |
| MS2 | 30 | 192.188.70.17/29 |
| MS2 | 40 | 192.188.70.25/29 |
 | MS6 | 99 | 192.188.70.33/29 |

---

### MS1 (solo tránsito, sin VLANs propias)

```
enable
configure terminal
ip routing
interface gig1/1/1
no switchport
ip address 10.4.70.1 255.255.255.252
exit
interface gig1/1/2
no switchport
ip address 10.4.70.5 255.255.255.252
exit
router ospf 1
network 10.4.70.0 0.0.0.3 area 0
network 10.4.70.4 0.0.0.3 area 0
end
write memory
exit
```

---

### MS7 (Edificio Izquierdo — SVIs 10, 20)

```
enable
configure terminal
ip routing
interface vlan 10
ip address 192.188.70.1 255.255.255.248
exit
interface vlan 20
ip address 192.188.70.9 255.255.255.248
exit
interface gig1/1/1
no switchport
ip address 10.4.70.18 255.255.255.252
exit
interface gig1/1/2
no switchport
ip address 10.4.70.6 255.255.255.252
exit
interface gig1/1/3
no switchport
ip address 10.4.70.14 255.255.255.252
exit
router ospf 1
network 10.4.70.4 0.0.0.3 area 0
network 10.4.70.12 0.0.0.3 area 0
network 10.4.70.16 0.0.0.3 area 0
network 192.188.70.0 0.0.0.7 area 0
network 192.188.70.8 0.0.0.7 area 0
passive-interface vlan 10
passive-interface vlan 20
end
write memory
exit
```

---

### MS2 (Edificio Derecho — SVIs 30, 40)

```
enable
configure terminal
ip routing
interface vlan 30
ip address 192.188.70.17 255.255.255.248
exit
interface vlan 40
ip address 192.188.70.25 255.255.255.248
exit
interface gig1/1/1
no switchport
ip address 10.4.70.2 255.255.255.252
exit
interface gig1/1/2
no switchport
ip address 10.4.70.9 255.255.255.252
exit
interface gig1/1/3
no switchport
ip address 10.4.70.13 255.255.255.252
exit
router ospf 1
network 10.4.70.0 0.0.0.3 area 0
network 10.4.70.8 0.0.0.3 area 0
network 10.4.70.12 0.0.0.3 area 0
network 192.188.70.16 0.0.0.7 area 0
network 192.188.70.24 0.0.0.7 area 0
passive-interface vlan 30
passive-interface vlan 40
end
write memory
exit
```

---

### MS6 (Centro — SVI 99)

```
enable
configure terminal
ip routing
interface vlan 99
ip address 192.188.70.33 255.255.255.248
exit
interface gig1/1/1
no switchport
ip address 10.4.70.17 255.255.255.252
exit
interface gig1/1/2
no switchport
ip address 10.4.70.10 255.255.255.252
exit
router ospf 1
network 10.4.70.8 0.0.0.3 area 0
network 10.4.70.16 0.0.0.3 area 0
network 192.188.70.32 0.0.0.7 area 0
passive-interface vlan 99
end
write memory
exit
```

```
enable
configure terminal
interface gigabitEthernet1/0/1
switchport mode access
switchport access vlan 99
exit
interface vlan99
ip address 192.188.70.33 255.255.255.248
ip helper-address 10.4.70.22
no shutdown
end
write memory
exit
```

---

**Notas:**
- `passive-interface` en las SVIs evita que OSPF envíe *hellos* hacia los hosts finales.
- Los switches MS8, MS9 (Izquierdo), MS3, MS4, MS5 (Derecho) **no necesitan** `ip routing` ni SVIs, ya que solo transportan las VLANs por trunk/EtherChannel hacia MS7 o MS2, que son los únicos con función de Capa 3 en su edificio.

**Verificación de configuración:**
```
show ip route
show ip ospf neighbor
show ip interface brief
```

---

## Servidores DHCP + DHCP Relay

### Subred de gestión para los servidores DHCP (pendiente desde el Paso 7)


| Enlace | Red / Prefijo | IP MS1 | IP Servidor |
|---|---|---|---|
| MS1 (Gig1/0/1) – DHCP1 | 10.4.70.20/30 | 10.4.70.21 | 10.4.70.22 |
| MS1 (Gig1/0/2) – DHCP2 | 10.4.70.24/30 | 10.4.70.25 | 10.4.70.26 |

---

### Configuración de MS1 (interfaces hacia los servidores + OSPF actualizado)

```
enable
configure terminal
interface gig1/0/1
no switchport
ip address 10.4.70.21 255.255.255.252
exit
interface gig1/0/2
no switchport
ip address 10.4.70.25 255.255.255.252
exit
router ospf 1
network 10.4.70.0 0.0.0.3 area 0
network 10.4.70.4 0.0.0.3 area 0
network 10.4.70.20 0.0.0.3 area 0
network 10.4.70.24 0.0.0.3 area 0
end
write memory
exit
```

---

### Configuración de los servidores (interfaz gráfica de Packet Tracer)

**DHCP1** — pestaña *Desktop → IP Configuration*:
```
IP Address: 10.4.70.22
Subnet Mask: 255.255.255.252
Default Gateway: 10.4.70.21
```

**DHCP1** — pestaña *Services → DHCP*, un pool por VLAN que sirve:

| Pool | Red | Máscara | Gateway por defecto | Rango IP inicio | Cantidad máx. |
|---|---|---|---|---|---|
| VLAN10 | 192.188.70.0 | 255.255.255.248 | 192.188.70.1 | 192.188.70.2 | 5 |
| VLAN20 | 192.188.70.8 | 255.255.255.248 | 192.188.70.9 | 192.188.70.10 | 5 |
| VLAN99 | 192.188.70.32 | 255.255.255.248 | 192.188.70.33 | 192.188.70.34 | 5 |

---

**DHCP2** — pestaña *Desktop → IP Configuration*:
```
IP Address: 10.4.70.26
Subnet Mask: 255.255.255.252
Default Gateway: 10.4.70.25
```

**DHCP2** — pestaña *Services → DHCP*:

| Pool | Red | Máscara | Gateway por defecto | Rango IP inicio | Cantidad máx. |
|---|---|---|---|---|---|
| VLAN30 | 192.188.70.16 | 255.255.255.248 | 192.188.70.17 | 192.188.70.18 | 5 |
| VLAN40 | 192.188.70.24 | 255.255.255.248 | 192.188.70.25 | 192.188.70.26 | 5 |

> En cada pool se debe desmarcar/excluir la IP del gateway si Packet Tracer no lo hace automáticamente, para que no se asigne a un cliente por error.

---

### DHCP Relay (`ip helper-address`) en las SVIs

Se aplica en la SVI de cada VLAN, apuntando hacia el servidor DHCP que la atiende:

**MS7 (VLAN 10, 20 → DHCP1)**
```
enable
configure terminal
interface vlan 10
ip helper-address 10.4.70.22
exit
interface vlan 20
ip helper-address 10.4.70.22
end
write memory
exit
```

**MS2 (VLAN 30, 40 → DHCP2)**
```
enable
configure terminal
interface vlan 30
ip helper-address 10.4.70.26
exit
interface vlan 40
ip helper-address 10.4.70.26
end
write memory
exit
```

**MS6 (VLAN 99 → DHCP1)**
```
enable
configure terminal
interface vlan 99
ip helper-address 10.4.70.22
end
write memory
exit
```

---

### Configuración de los clientes finales

Cada PC/Laptop se configuró su modo de IP en **DHCP** (no estático), desde *Desktop → IP Configuration → DHCP*, en todos los dispositivos: PC0, PC1, PC2, PC3, PC4, Laptop0, Laptop1, Laptop2, Laptop3.

**Verificación de configuración:**
```
show ip dhcp binding    (en los servidores, si aplica)
show ip interface brief (en MS7, MS2, MS6, para confirmar helper-address activo)
```
> En cada PC/Laptop, `ipconfig` desde su terminal debe mostrar una IP dentro del rango de su VLAN correspondiente.


## Configuración de ACLs (Naranja / Verde / ADMIN)

### Diseño de la política

| VLAN | Subred | Puede comunicarse con | Bloqueada hacia |
|---|---|---|---|
| Naranja-IZQ (10) | 192.188.70.0/29 | Naranja-DER (30) | Verde-IZQ, Verde-DER, ADMIN |
| Naranja-DER (30) | 192.188.70.16/29 | Naranja-IZQ (10) | Verde-IZQ, Verde-DER, ADMIN |
| Verde-IZQ (20) | 192.188.70.8/29 | Verde-DER (40) | Naranja-IZQ, Naranja-DER, ADMIN |
| Verde-DER (40) | 192.188.70.24/29 | Verde-IZQ (20) | Naranja-IZQ, Naranja-DER, ADMIN |
| ADMIN (99) | 192.188.70.32/29 | Todas (sin restricción) | — |

---

### MS7 (Edificio Izquierdo — VLAN 10 y 20)

```
enable
configure terminal
ip access-list extended NARANJA_IZQ_ACL
remark Permite comunicacion con VLAN Naranja Edificio Derecho
permit ip 192.188.70.0 0.0.0.7 192.188.70.16 0.0.0.7
remark Bloquea comunicacion hacia VLAN Verde Izquierdo
deny ip 192.188.70.0 0.0.0.7 192.188.70.8 0.0.0.7
remark Bloquea comunicacion hacia VLAN Verde Derecho
deny ip 192.188.70.0 0.0.0.7 192.188.70.24 0.0.0.7
remark Bloquea comunicacion hacia VLAN ADMIN (trafico unidireccional)
deny ip 192.188.70.0 0.0.0.7 192.188.70.32 0.0.0.7
remark Permite el resto del trafico (DHCP, servicios generales)
permit ip any any
exit
ip access-list extended VERDE_IZQ_ACL
remark Permite comunicacion con VLAN Verde Edificio Derecho
permit ip 192.188.70.8 0.0.0.7 192.188.70.24 0.0.0.7
remark Bloquea comunicacion hacia VLAN Naranja Izquierdo
deny ip 192.188.70.8 0.0.0.7 192.188.70.0 0.0.0.7
remark Bloquea comunicacion hacia VLAN Naranja Derecho
deny ip 192.188.70.8 0.0.0.7 192.188.70.16 0.0.0.7
remark Bloquea comunicacion hacia VLAN ADMIN (trafico unidireccional)
deny ip 192.188.70.8 0.0.0.7 192.188.70.32 0.0.0.7
remark Permite el resto del trafico (DHCP, servicios generales)
permit ip any any
exit
interface vlan10
ip access-group NARANJA_IZQ_ACL in
exit
interface vlan20
ip access-group VERDE_IZQ_ACL in
end
write memory
exit
```

---

### MS2 (Edificio Derecho — VLAN 30 y 40)

```
enable
configure terminal
ip access-list extended NARANJA_DER_ACL
remark Permite comunicacion con VLAN Naranja Edificio Izquierdo
permit ip 192.188.70.16 0.0.0.7 192.188.70.0 0.0.0.7
remark Bloquea comunicacion hacia VLAN Verde Izquierdo
deny ip 192.188.70.16 0.0.0.7 192.188.70.8 0.0.0.7
remark Bloquea comunicacion hacia VLAN Verde Derecho
deny ip 192.188.70.16 0.0.0.7 192.188.70.24 0.0.0.7
remark Bloquea comunicacion hacia VLAN ADMIN (trafico unidireccional)
deny ip 192.188.70.16 0.0.0.7 192.188.70.32 0.0.0.7
remark Permite el resto del trafico (DHCP, servicios generales)
permit ip any any
exit
ip access-list extended VERDE_DER_ACL
remark Permite comunicacion con VLAN Verde Edificio Izquierdo
permit ip 192.188.70.24 0.0.0.7 192.188.70.8 0.0.0.7
remark Bloquea comunicacion hacia VLAN Naranja Izquierdo
deny ip 192.188.70.24 0.0.0.7 192.188.70.0 0.0.0.7
remark Bloquea comunicacion hacia VLAN Naranja Derecho
deny ip 192.188.70.24 0.0.0.7 192.188.70.16 0.0.0.7
remark Bloquea comunicacion hacia VLAN ADMIN (trafico unidireccional)
deny ip 192.188.70.24 0.0.0.7 192.188.70.32 0.0.0.7
remark Permite el resto del trafico (DHCP, servicios generales)
permit ip any any
exit
interface vlan30
ip access-group NARANJA_DER_ACL in
exit
interface vlan40
ip access-group VERDE_DER_ACL in
end
write memory
exit
```

---

### MS6 (Centro — VLAN 99 ADMIN)

No requiere ACL de salida ya que ADMIN tiene acceso completo a todas las VLANs por diseño. Se documenta explícitamente para dejar constancia de la decisión:

```
enable
configure terminal
ip access-list extended ADMIN_ACL
remark VLAN ADMIN tiene acceso completo, sin restricciones de salida
permit ip any any
exit
interface vlan99
ip access-group ADMIN_ACL in
end
write memory
exit
```

---

### Verificación de configuración

```
show access-lists
show ip interface vlan10
show ip interface vlan20
show ip interface vlan30
show ip interface vlan40
```

---

