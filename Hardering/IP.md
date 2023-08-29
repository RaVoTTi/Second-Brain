### Obsoletos
arp = ip n (ip neighbor), 
ifconfig = ip a (ip addr), ip link, ip -s (ip -stats) 
netstat = netstat -r [ss, ip route ], netstat -i [ip -s link], netstat -g [ip maddr]
route = ip r (ip route)

### IP
Sintaxis 
ip [ opciones ] OBJETO [ comando [ argumento ] ]
#### OBJETOS
##### ***link***
para configurar los objetos fisico o logicos de la red
ip link set enp0s3 up/down
ip link set dev enp0s3 arp up/down


##### ***address***
manejo de direcciones asociadas a los diferentes dispositivos
ip addr show / ip -c a // -c = colorear
ip addr add 192.168.1.4/24 dev enp0s3
ip addr del 192.168.1.4/24 dev enp0s3

##### ***neighbour***
administrar enlaces de vecindad
##### ***rule***
ver las politicas de enrutado y cambiarlas
##### ***route***
ver las tablas de enrutado y cambiar las reglas de las tablas
ip route show
ip route add 10.10.50.0/24 via 192.168.1.1 dev enp0s3
ip route del 10.10.50.0/24
ip route add default via 192.168.1.1

##### ***tunnel***
administrar los tuneles IP
##### ***maddr***
ver las direcciones multienlace, sus propiedades y cambiarlas
##### ***mroute***
establecer, cambiar o borrar enrutado multienlace
##### ***monitor***
monitorizar continuamente el estado de los dispositivos direcciones y rutas

