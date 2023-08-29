## /etc/pass
se guardan los usuarios del sistema, las contrasenas se guardan en shadow

## useradd
-d directorio home
-m crea el directorio home
-g grupo principal
-k directorio plantilla
-s interprete de comandos, terminal
-G grupo secundario

## /etc/group
fichero donde se guardan los grupos y quienes pertenencen a ellos de forma secundaria

## /etc/skel
directorio por defecto para crear usuarios, es una plantilla lo declaras con la flag -k

## newgrp
para envia el grupo como grupo principal

## getend
comando para obtener info sobre usuarios y grupos
## groupdel
## groupmod
## userdel
## usermod
modifica usuarios, tiene las mismas flags que useradd
usermod -a -G group user porque usermod -G group user lo asigna a ese 
## userdel

-r para elimininar toda la info y el directorio

## /etc/shadow
ficjero donde se guardan las contrasenas cifradas,

example fasedaff:$6$sdasdsad6$/ddslfkjdskjfbakhbaladakbscbsh.asndlsabdkash.ns1
:12312:0:99999:7:::

Contrasena cifrtada con formato $id$salt$hashed el $id indica el algoritmo de cifrado `$1$` MD5, `$2a$` o `$2y$` Blowfish, `$5$` SHA-256 y `$6$` SHA-512

## /nologin & /false
usuarios del sistema
### /nologin
no tiene disponible el interprete
### /false
no hace nada no contiene shell












## passwd 
para bloquear un usuario -l, root puede cambiar cualquier usuario
