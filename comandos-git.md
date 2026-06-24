## Crear repositorio

git init

## Agregar archivos

git add .

## Versionar o "Commitear"

git commit -m 'comentario'

## Ver estado de nuestro repertorio

git status

## Ver historial del repertorio

git log 

## Renombrar rama maestra a main

git branch -M main

## Eliminar un archivo (transformarlo en untracked)

git rm --cached <archivo>

## Añadir origen remoto

git add origin <url-exacta-del-repositorio>

## Revisar origen remoto

git remote -v

## Modificar origen remoto

git remote set-url origin <url-exacta-del-repositorio>

## Enviar contenido a la nube

git push -u origin main