### who
indica quien esta identidicado en el sistema
### w 
muestra quien hay y que esta ejecutando
### last
lista los ultimos accesos que ha tenido el sistema
	-p los logueos de un dia

### /etc/login.defs
#### Gestion
UMASK Establece mascara de de permisos para los nuevos directorios home que se crean en el sistema. Por defecto 022, mejor 077. Es a la inversa
#### Administracion
LOGIN_RETRIES
#### Contrasena /etc/login.defs
PASS_MAX_DAYS
PASS_MIN_DAYS
PASS_WARN_AGE alerta a los tantos dias de que  va a caducar
ENCRYPT_METHOD defecto SHA512
PAM


