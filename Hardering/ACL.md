## getfacl
Muestra uno o varios elementos
## setfacl
Configura la ACL de uno o varios elementos
	-m modifica la ACL
	-R recursivo
	-x elimina un permiso
	-b elimina toda la ACL
	-d los nuevos elementos de un directorio heredan su misma ACL
ejemplos
setfacl -m u:ana:r-x carta.txt
setfacl -Rm g:profesores:rw /home/profesores
setfacl -b carta.txt
se ver un + cuando tiene un ACL
### Mascara
define el limite mas permisivo que puede tener cualquier permiso establecido en su ACL. Siempre tendra preferencia respecto al resto de permisos establecidos
Se define usando la letra m(mask) setfacl -m m::r foto.jpg