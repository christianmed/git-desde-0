### Git Branch
El comando:
```
git branch
```
Lista todas las ramas del proyecto.

El comando:
```
git branch nombre_rama
```
Se crea una nueva rama con el nombre nombre_rama

Con el comando:
```
git checkout nombre_rama
```
Nos podemos mover a una rama específica.

Nosotros podemos crear cuantas ramas queramos y/o necesitemos. Las ramas nuevas que se rean apuntan al commit actual.

Con el comando:
```
git branch -d nombre_rama
```
Borramos la rama nombre_rama si es que ya fue fusionada con la rama actual.

Con el comando:
```
git branch -D nombre_rama
```
Borramos la rama nombre_rama haya sido o no fusionada con la rama actual. Su fuerza el borrado y se pierden todos los cambios.

Con el comando:
```
git branch --no-merged
```
Mostramos cuáles ramas no han sido fisionadas con la rama actual.

Con el comando:
```
git branch --merged
```
Mostramos cuáles ramas han sido fusionadas con la rama actual.

Con el comando:
```
git checkout -b name_branch
```
De forma simultánea creamos una nueva rama llamada branch_name y saltamos o nos movemos a ella.
