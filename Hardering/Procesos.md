Un proceso no es un programa, porque puedo tener varios procesos de un mismo programa.
### PS
-e todos los procesos
-f mas info
-e(PID) 
-aux = nos muestra como se ha ejecutado, tambien el porcentaje de cpu y memoria
l muestra prioridad
-F muestra otro formato

STAT = estado que se encuentra el proceso, S = sleeping, R = running, T = stop, zombie no deberia haber nunca ninguno
NI = prioridad
### PSTREE
muestra los procesos en una jerarquia, en forma de arbol
### TOP
Info en tiempo real
load average, la primer columna es la media del ultimo minuto, la segunda es la media de los ultimos 5 minutos y la tercera columna es la media de los ultimos 15 minutos.
-n 1 =  vez
#### FREE
uso de la memoria
-h human readable
#### UPTIME
tiempo del servidor

#### PGREP
te devuelve el PID si coincide la regex con el nombre del proceso

-l te da el nombre
-u proceso de tal usuario
### HTOP
Esta muchisimo mejor

dd if=/dev/zero of=/dev/null
stress

