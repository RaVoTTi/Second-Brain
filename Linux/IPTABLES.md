iptables [-t tabla] -A/I cadena [opciones] -j accion

example
iptables -t filter -A INPUT -p icmp -j accept

defalt -t filter
iptables -A INPUT -p icmp -j accept 

