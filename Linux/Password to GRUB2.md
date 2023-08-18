grub-mkpasswd-pdkdf2 "pasamos solo el hash" > /etc/grub.d/40_custom

set superusers='<Cualquier root>'

passwd_pdkdf2 <root> <hash>

grub-mkconfig -o /boot/grub/grub.cfg



Cuando va el menu de grub apretas la tecla e y podes modificar el grub, en ese menu vas a la linea linux, donde dice "ro" cambias por rw y pones "init=bash" por quiet.
