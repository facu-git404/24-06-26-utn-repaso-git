## ¿Para que sirve git?

Para versionar nuestro proyecto

## ¿Que es github?

Es uno de los servicios que permiten alojar (hostear) nuestro repositorio en la nube

## ¿Como creo un repositorio con git?

Con el comando "git init", inicializamos nuestro repositorio local

## ¿Como podemos versionar nuestro codigo? Es decir, tengo cambios y quiero "guardar partida"

git add (nombre del archivo) / git add . (trae todos los archivos en el directorio/carpeta del proyecto)

git commit -m 'comentario descriptivo del cambio' (Para crear un checkpoint/foto/version de como esta el proyecto actualmente)

## ¿Que es el directorio raiz?

Es la carpeta del proyecto

## ¿Como podemos subir nuestro repositorio a la nube (asumiendo que ya estamos conectados)?

Depende, si es tu primera vez pusheando: git push -u origin main

Pero si ya existe la main: git push

## ¿Que es el Source Control?

Es una forma de aplicar comandos basicos de git sin escribir codigo, como "git add ."

## ¿Como desplegar la pagina?

Tenes que tener el github en publico e ir a settings > pages, luego Branches, y por ultimo donde dice none elegimos la opcion "main" y podremos ver nuestra pagina en github.
Si tenemos el github en privado vamos a requerrir servicios de pago como:

github pages
vercel
railway
hostinger
cloudways

hay opciones mas complejas que sirven como nube como:

AWS
GCP

y la mas compleja pero valida es de forma local:

VPS