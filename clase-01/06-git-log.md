### Git Log
Muestra el historial de commits

`git log --pretty=format:"%h - %an, %ar : %s"`
Muestra el historial con el formato que indicamos.

`git log --after:"2017-02-15 00:00:00"`
Muestra el historial de cambios después del 15/02/2017.

`git log --before:"2017-02-15 00:00:00"`
Muestra el historial de cambios antes del 15/02/2017.

### Limitar la salida del historial
`git log -n` nos muestra los n commits mas recientes.
