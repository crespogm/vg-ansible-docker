-----
**En la terminal**
```
vagrant up
vagrant ssh
docker ps
curl localhost:8000
```
**En la navegador**
```
En linux ingresar a:
localhost:8000
En windows con WSL2 ingresar a:
172.21.160.1:8000
```
**Explorar otras soluciones de docker compose*
```
Descargar el repo de Awesome Docker config en otra carpeta
https://github.com/docker/awesome-compose.git
Reemplazar los archivos en la carpeta ansible-docker
Leer el docker compose y reemplazar los puertos que se exponen en la Vagrantfile
```