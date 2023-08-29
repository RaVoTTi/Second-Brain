## chgrp 
cambia de grupo de un elemento
## chown
 cambia el usuario y el grupo de uno o mas elementos. La opcion -R hace que sea recursivo
 example
 ```chown fasedaff:fasedaff folder```
 
## Chmod 
chmod +x

chmod u+r,g+x
chmod u=rx,g=x
chmod 510

## Permisos especiales
Suman funcionalidades, solucionan carencias que proveen los permisos de lectura, escritura y ejecucion. la s o la t reemplaza la x
### SetUID 4 u+s
El programa que lo tenga activado se ejecutara con los permisos del usuario propietario del fichero y no con los permisos de quien invoca al programa. Se representa por la letra S como permiso de ejecucion
Si la s esta en el conjunto del usuario pertenece aca
Si la S esta en mayuscula significa que no tiene permiso de ejecucion, en minuscula si
### SetGID 2 g+s
Igual que setUID pero con los permisos del grupo. En caso de ser directorio los elementos creados perteneceran al grupo del directorio y no al grupo del usuario que crea el elemento
Si la s esta en el conjunto del usuario pertenece aca
## Sticky Bit 1 o+t
En el directorio que lo tenga activado, los ficheros que contenga solo podran ser borrados por sus propietarios. Se representa por t en el permiso de ejecucion de los otros. Si la T esta en mayuscula significa que no tiene permiso de ejecucion, en minuscula si


