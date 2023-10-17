## Instalación
Instalación y Configuración de DHCP (Dynamic Host Configuration Protocol):
```
sudo apt-get install isc-dhcp-server
```
Configuración: Abre el archivo /etc/dhcp/dhcpd.conf y define las configuraciones necesarias para tu red, como rangos de direcciones IP y opciones de configuración. Luego, reinicia el servicio:
```
sudo systemctl restart isc-dhcp-server
```
