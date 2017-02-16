## git tag
Permite agregar atiquetas a los commits

Hay dos tipos de etiquetas:
1. Etiquetas ligeras
2. Etiquetas anotadas

### Etiquetas ligeras
Actuan como un alias para un commit o apuntan a un commit. El comando es:
```
git tag mi_etiqueta
```
Se usan para marcar puntos en nuestros projectos no tan importantes como una versión estable.

### Etiquetas anotadas
Se guardan en la base de datos de Git como objetos enteros. Contienen el nombre del etiquetador, correo electrónico, fecha de creación y un mensaje con una descripción del estado del projecto en ese punto del tiempo. El comando es:
```
git -a mi_etiqueta -m "mi_mensaje"
```
Se usan para marcar puntos importantes en nuestros proyectos tales como versiones estables, etc.
