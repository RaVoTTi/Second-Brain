Los atributos son marcas en un elemento de un sistema de ficheros compatible, que indican propiedades especiales respecto a como se va a comportar dicho elemento. Hay varios, 
	i = solo lectura, inmutable
	a = solo se puede anadir datos al fichero, util para ficheros log
	A = no se actualiza la marca de tiempo del ultimo acceso
	s = cuando se borra el fichero se eliminan de forma segura
	u = cuando se boora el fichero sus datos se conservan en el disco
	e = El archivo usa extensiones para guardar la informacion en disco. Esto reduce la fragmentacion. Activa por defecto para los sistemas de ficheros modernos
### lsattr
lista los atributos de los elementos que le indiquemos
	-R recursivo
	-a Muestra elementos ocultos
	-d Muestra los atributos de un directorio
### chattr
Modifica los atributos de los elementos que le indiquemos.
	-R recursivo
	-f Ignora msj de error

## stat 
fecha de acceso y modificacion