Socket Statiscs
Obtiene informacion sobre los sockets (internos y de red). Sin parametros lista todas las conexiones actuales. Sintaxis
ss [ options ]  [ filter ]
#### OPCIONES
-t = TCP
-U = UDP
-l = socket a la escucha de un puerto
-p = Muestra el nombre y PID del proceso asociado a cada conexion
-s = Estadisticas resumidas
-n = no los nombres, mostrar las ip
ss -nltp

#### FILTROS
state = puertos deben estar en ESTABLISED, LISTENING, CLOSED, CONNECTED, TIME-WAIT
exclude = excluir los que esten en tal estado
EXPRESION (and or y not)
(origen y destino) {src | dst}
(puerto de origen/destino) { dport | sport } {eq | neq }

example
ss state stablised '(sport = :http or sport = :https)' src 192.188.1.0/24
ss sport neq :21 and sport neq :https or not dst 198.133.8.0/24
