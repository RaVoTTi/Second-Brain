

## REGLAS
SINTAXIS: accion protocolo origen puerto_origen -> destino puerto_destino (opciones)
ejemplo: alert ip 8.8.8.8 53 -> 192.168.0.0/24 53 (msg: "DNS", sid: 1000001)

### ACCIONES
alert, log, pass, dynamic, drop, reject
### PROTOCOLO
TCP UDP ICMP E IP O any
### OPCIONES
msg 
sid  mayor a 1 millon


### LINKS
https://www.incibe.es/incibe-cert
https://snort-org-site.s3.amazonaws.com/production/document_files/files/000/000/596/original/Rules_Writers_Guide_to_Snort_3_Rules.pdf
