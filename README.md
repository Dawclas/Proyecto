#  Proyecto Docker


**Tabla de Contenidos**



## Ejercicio Inicial
Crear un contenedor demonio a partir de la imagen nginx , el contenedor se debe llamar servidor_web y se debe acceder a él utilizando el puerto 8181 del ordenador donde
tengas instalado docker.

`$ docker run -d --name servidor_web -p 8181:80 nginx `

`$ docker ps`

`$ docker images`

`$ docker stop servidor_web`

`$ docker ps`

`$ docker rm servidor_web`

`$ docker ps -a`

1. Pantallazo donde se vea la creación del contenedor y podamos comprobar que el contenedor está funcionando.

![](https://github.com/Dawclas/Proyecto/blob/39abd8b102a4be6163a0c7411df5530d04b0ff38/Capturas/Captura1.PNG)

2. Pantallazo donde se vea el acceso al servidor web utilizando un navegador web (recuerda que tienes que acceder a la ip del ordenador donde tengas instalado
docker)

![](https://github.com/Dawclas/Proyecto/blob/39abd8b102a4be6163a0c7411df5530d04b0ff38/Capturas/Captura2.PNG)

3. Pantallazo donde se vean las imágenes que tienes en tu registro local.

![](https://github.com/Dawclas/Proyecto/blob/39abd8b102a4be6163a0c7411df5530d04b0ff38/Capturas/Captura3.PNG)

4. Pantallazo donde se vea cómo se elimina el contenedor (recuerda que antes debe
estar parado el contenedor).

![](https://github.com/Dawclas/Proyecto/blob/39abd8b102a4be6163a0c7411df5530d04b0ff38/Capturas/Captura5.1.PNG)

## Ejercicio trabajo con imágenes
### Servidor Web
### Servidor de base de datos
## Ejercicio Almacenamiento
### Bind mount para compartir datos

1. Crea una carpeta llamada *saludo* y dentro de ella crea un fichero llamado *index.html* con el siguiente contenido (Deberás sustituir ese XXXXXx por tu
nombre.):

```html
        <h1>HOLA SOY XXXXXX</h1>
```




### Links

[Links](http://localhost/)

[Links with title](http://localhost/ "link title")

`<link>` : <https://github.com>

[Reference link][id/name] 

[id/name]: http://link-url/

GFM a-tail link @pandao

### Code Blocks (multi-language) & highlighting

#### Inline code

`$ npm install marked`


#### HTML code

```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>
```




