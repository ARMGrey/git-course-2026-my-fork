# Notes
Notas mías, si si muchas notas.
## Git Branch

## Git checkout

Git checkout sirve para intercambiar ramas o commits.

- `git switch <rama>`: Cambiar a una rama

- `git add .` Añadir todos los archivos al staging. Incluyendo archivos nuevos.
- `git add -u` Añadir SOLO los archivos cambiados al area de staging. No añade los archivos nuevos.

## Git commit
Guarda los cambios del staging area.

- `git commit -m "Comentario"`: Hace un commit con un comentario.
- `git commit -am "Comentario"` Es el equivalente de:
```bash
git add -u
git commit -m "Comentario"
```
## Git push
Subir cambios al *remote* (server)
- `git push <remote> <branch>`: subir los cambios de nuestra branch al server remote.

Por default tenemos a nuestro remote principal llamado *origin* (GitHub). Por defecto un push usa la rama main/master de origin, pero al ahora estar en la rama "notas" (una rama alterna), ahora debemos especificar la rama al a que se debe subir.

`git push -u origin <branch>`

Si cambiamos la branch upstream podremos pushear nuestros cambios sin especificar a que rama todo el tiempo.

