### Git Remote
El comando:
```
git remote
```
Lista los ... locales del preyecto.

Con el comando:
```
git remote add nombre_ url
```
Vinculamos nuestros repositorio local con Github en donde el nombre corresponde a ... y el url será el url de neustro repositorios en Github. Por ejemplo:
```
git remote add prueba https://github.com/christianmed/git-desde-0.git
```

## Pasos para aportar a otro repositorio
1. Hacer un fork del proyecto en Github.
2. Clonar el repositorio desde mi cuenta de Github.
3. Crear una rama local.
4. Realizar los cambios en la nueva rama local.
5. Confirmar los cambios que realicemos.
6. Hacer push de mis cambios (enviar los commits locales a Github) con el comando `git push origin nombre_rama`.
7. Crear un pull request con la nueva rama de mi repositorio en Github.
8. Esperar que el administrador del repositorio original acepte mis cambios.

Con el comando:
```
git push origin --delete nombre_rama
```
Eliminamos una rama en nuestro repositorio en Github.
