# Proyecto 2 :triangular_flag_on_post:
### Integrantes
Carne | Nombre |
|-----|-----|
|201902714 | Kevin Josué Calderón Peraza | 
|201901016 | Kevin Alfredo López Rodríguez |
|201902308 | Samuel Isaac Pérez Pérez |
|201213487| Vania Argueta Rodríguez |

## Requerimientos GNS3
* Versión: **2.2.10**
* Sistema operativo: **Windows 10 u 11**
* Imagenes IOS: **Imagen de Ethernetswitch (Switch de Capa 3)** (porporcionada por el tutor)
* VirtualBox: **Imagen ISO, Ubuntu 20.04**

## TOPOLOGIA 1 :boom:

<img src="Docs/TOPO1.PNG"  width="75%" height="75%">

### Direcciones IP - FLSM

Subred | Network | Mascara de subred | P Asignable | U Asignable | Broadcast | Cantidad de host |
|-----|-----|-----|-----|-----|-----|-----|
| Subred 1 | 10.5.0.0 | 255.255.224.0 | 10.5.0.1 | 10.5.31.254 | 10.5.31.255 |  8190 | 
| Subred 2 | 10.5.32.0 | 255.255.224.0 | 10.5.32.1 |	10.5.63.254	| 10.5.63.255 | 8190 |
| Subred 3 | 10.5.64.0 | 255.255.224.0 | 10.5.64.1 | 10.5.95.254	| 10.5.95.255 | 8190 |
| Subred 4 | 10.5.96.0 | 255.255.224.0 | 10.5.96.1 |	10.5.127.254 |	10.5.127.255 | 8190 |
| Subred 5 | 10.5.128.0 | 255.255.224.0 | 10.5.128.1 |10.5.159.254 |	10.5.159.255 | 8190 |
| Subred 6 | 10.5.160.0 | 255.255.224.0 | 10.5.160.1 |	10.5.191.254 |	10.5.191.255 | 8190 |

### R

### Configuraciones de la Nubes


## TOPOLOGIA 2 :boom:

<img src="Docs/T2.PNG"  width="75%" height="75%">

### Direcciones IP - VLSM

VLAN | Network | Mascara de subred | P Asignable | U Asignable | Broadcast | Cantidad de host |
|-----|-----|-----|-----|-----|-----|-----|
| 10 | 192.168.45.192 | 255.255.255.224 | 192.168.45.193 | 192.168.45.222 | 192.168.45.223 | 30   | 
| 20 | 192.168.45.224 | 255.255.255.240  | 192.168.45.225  |	192.168.45.238	| 192.168.45.239 | 14  |
| 30 | 192.168.45.0 | 255.255.255.128 | 192.168.45.1 | 192.168.45.126 | 192.168.45.127 | 126  |
| 40 | 192.168.45.128 | 255.255.255.192  | 192.168.45.129 | 192.168.45.190 | 192.168.45.191	| 62  |

## TOPOLOGIA 3 :boom:

<img src="Docs/T3.png"  width="75%" height="75%">

### Direcciones IP - VLSM

VLAN | Network | Mascara de subred | P Asignable | U Asignable | Broadcast | Cantidad de host |
|-----|-----|-----|-----|-----|-----|-----|
| 10 | 192.168.55.192 | 255.255.255.224 | 192.168.55.193 | 192.168.55.222 | 192.168.55.223 | 30   | 
| 20 | 192.168.55.224 | 255.255.255.240 | 192.168.55.225 |	192.168.55.238 | 192.168.55.239 | 14 |
| 30 | 192.168.55.0 | 255.255.255.128 | 192.168.55.1 | 192.168.55.126 | 192.168.55.127 | 126 |
| 40 | 192.168.55.128 | 255.255.255.192 | 192.168.55.129 | 192.168.55.190 | 192.168.55.191 | 62  |
