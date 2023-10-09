### Docker Notes

- Crear app.js
- Crear Dockerfile
- Docker Build

```
docker build -t hola-evelyn .
```
# Listar las imagenes
```
docker image ls
```
# Ejecutar el contenedor
```
docker run hola-evelyn
```
# Rutas

Rutas absolutas:
Comienzan con /var/log

Rutas relativas:
Comienzan con ./log

# Variable de entorno persistente

echo MIVARIABLE="La variable de entorno" >> .bashrc

source .bashrc

Fix: command not found
nano .bashrc y poner "" a la variable de entorno




