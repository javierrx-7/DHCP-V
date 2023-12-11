# Dockerfile

## Instalar paquete isc-dhcp-server

    sudo apt isc-dhcp-server

## Editar para una configuración básica /etc/dhcp/dhcpd.conf

    sudo nano /etc/dhcp/dhcp.conf

- Seguimos lo que indica en las imagenes subidas

## Editar para configurar la interfaz de red /etc/Default/isc-dchp-server

    sudo nano /etc/Default/isc-dhcp-server

- Seguimos lo que indica en las imagenes subidas

## Declarar una subnet 172.16.0.0/16

- Seguimos lo que indica en las imagenes subidas

## Arranca el servicio con systemctl

    sudo nano /etc/sysctl.conf

- Seguimos lo que indica en las imagenes subidas

## Comprueba el servicio con "systemctl status"

    systemctl status javierserver

- Seguimos lo que indica en las imagenes subidas

## Prueba con el cliente que se le asigna un ip en el rango 

- Seguimos lo que indica en las imagenes subidas

## Declarar una asignación por mac fija a 172.16.0.5

- Seguimos lo que indica en las imagenes subidas

## Prueba con otro cliente que se le asigna la ip fija

- Seguimos lo que indica en las imagenes subidas

## Comprueba con el wireshark los mensajes del protocolo

- Seguimos lo que indica en las imagenes subidas