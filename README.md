# Guia

## Trabajar con ramas

1. Cada usuario tiene su propia rama, donde cada persona utilizara su propia rama para hacer sus tareas.
2. Cada vez que una persona haga un push en la rama main, los demas participantes tendran que hacer un rebase.
3. Recordad hacer el push en vuestra rama!

## Comandos utiles

- `git add .` // Comando para añadir archivos modificados al area Staging.
- `git commit -m "mensage de la featured"` // Confirmar cambios y añadir mensaje a la modificación
- `git push origin nombreRama` // Subir cambios de una rama
- `git pull origin nombrerama` // Obtener cambios de una rama
- `git rebase main` // Obtener los commits de la rama main a nuestra rama actual.
  > Muy importante hacer rebase cuando un integrante añada una funcionalidad al main
