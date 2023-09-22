# Trabajando con imagenes.
### Images namespaces.
### Root-like. 
```
ubuntu
```
### User (and organizations)
```
gdiaz/nginx
```
### Self-Hosted
```
registry.example.com:5000/my-private-image
```
### Buscando un contenedor <ubuntu>

```
docker search ubuntu
```
### Ejecutando un contenedor <ubuntu>
-i tells Docker to connect us to the container's stdin.
-t tells Docker that we want a pseudo-terminal.

```
docker run -it ubuntu
```
```
apt-get update
```
```
apt-get install figlet
```
