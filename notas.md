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
