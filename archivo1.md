# Práctica 2: Instalación y configuración de servidor y cliente DHCP en Debian.
## Índice
[1. Introducción](#introducción)  
[2. Recursos ](#recursos)  
[3. Configuración de la tarjeta red](#configuración-de-la-tarjeta-red)  
[4. Cambiar a Superusuario](#cambiar-a-superusuario)  
[5. Istalación del paquete](#instalación-del-paquete)  
[6. Configuración](#configuración)  
[7. Configuración del servicio dhcp](#configuración-del-servicio-dhcp)  
[8. Comprobación dhcp](#comprobación-dhcp)  
[9. Comprobación en el cliente con reserva](#comprobación-en-el-cliente-con-reserva)  
[10. Comprobación en el cliente sin reserva](#comprobación-en-el-cliente-sin-reserva)  
[7. Ejercicio 5](#ejercicio-5)  
[7. Ejercicio 5](#ejercicio-5)      

## Introducción
Esta actividad consiste en realizar un tutorial en el que se describan los ficheros involucrados y los comandos necesarios para configurar el servidor isc-dhcp-server en Debian.

## Recursos
o	PC con acceso a Internet y paquete ofimático instalado.  
o	VirtualBox  
o	Debian  
o	Windows cliente  
o	pfSense  
o	https://github.com/  
o	Visual Studio Code 

## Configuración de la tarjeta red

### Enunciado

En las captura siguiente se va a mostrar la configuración de la tarjeta de red mediante interfaz grafica.

### Práctica

![Configuración-de-red](files/Captura1.PNG)

## Cambiar a Superusuario

### Enunciado

Se va ha cambiar a el superusuario para poder instalar el servicio, utilizaremos el comando __su -__

### Práctica

![Cambio-de-usuario](files/Captura2.PNG)

## Instalación del paquete

### Enunciado

En este apartado vamos ha instalar el paquete dhcp

### Práctica

![Instalación](files/Captura3.PNG)

## Configuración

### Enunciado

Configuración de la interfaz por la que va ha escuchar

### Práctica

![Copia](files/Captura5.PNG)
![Configuración](files/Captura4.PNG)

## Configuración del servicio dhcp

### Enunciado

A continuación, vamos ha modificar el archivo dhcpd.conf para configurar el servicio dhcp

### Práctica

![copia dhcpd.conf](files/Captura6.PNG)   
Realizamos una copia del archivo dhcpd.conf  
___
![configuracion_dhcp.conf](files/Captura7.PNG)  
Configuramos las opciones del dhcp
___
![configuracion_de reserva](files/Captura8.PNG)  
Configuración de la reserva de ip

## Comprobación dhcp

### Enunciado

Comprobación del estado del servidor dhcp

### Práctica

![comprobación_dhcp](files/Captura9.PNG) 

## Comprobación en el cliente con reserva

### Enunciado

Comprobación en el cliente con reserva

### Práctica

![comprobación_reserva](files/Captura10.PNG)
![comprobación_reserva_ping](files/Captura12.PNG) 

## Comprobación en el cliente sin reserva

### Enunciado

Comprobación en el cliente sin reserva

### Práctica

![comprobación_cliente](files/Captura11.PNG)
![comprobación_cliente_ping](files/Captura13.PNG)

## Ejercicio

### Enunciado



### Práctica

## Ejercicio

### Enunciado



### Práctica

## Ejercicio

### Enunciado



### Práctica

## Ejercicio

### Enunciado



### Práctica
## Ejercicio

### Enunciado



### Práctica
## Ejercicio

### Enunciado



### Práctica
