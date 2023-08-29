docker run -it --rm archlinux bash -c "echo hello world"
-d = no esta anclado = detachet
-it = interactivo y util para una shell
--name 
docker inspect
# PS
-q = only ids
-a = all
-f = filter
--format =  te formatea
# Exec
exec -it name bash

# CP

# Commit
crear un contenedor a partir de otro

docker commit apache miweb:latest

Docker build crea una imagen usando el ficjero Dockerfile
### FROM
### RUN
### WORKDIR
### COPY
### ENV

### EXPOSE
### CMD
### ARG

docker run -v /dir_anfi/:/dir_cont/ llevamos el contenido del directorio origen del anfitrion al contenedor, como montaje en linux
docker run -v /dir_cont/ se crea un volumen que usaran en el directorio /dir_cont/
docker run -v nombre:/dir_cont/ igual que el anterior pero con nombre




