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


# Capturas de la topología completa

<div align="center">
  <img src="img/Topologia_sin_etiquetas.png" alt="" width="100%">
</div>

# Topología etiquetando los tipos de interfaces y medios de transmisión.

<div align="center">
  <img src="img/Topologia_sin_etiquetas.png" alt="" width="100%">
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

---




















