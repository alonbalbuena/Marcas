#Tabla de contenidos
- [Clases abstractas](#clases-abstractas)
      - [Métodos abstractos:](#m%C3%A9todos-abstractos)

***

# Clases abstractas

Al crear una relacion de herencia habra ocasiones en las que por ahorrar código se realizaran clases, de más, aunque no tengan un sentido a nivel de objeto.

En este caso hay varios tipos de articulos, los cuales son unicos para cada tipo, y siempre perteneceran a estos tipos solo. Por tanto la clase **ARTICULO** nunca va a ser tocada (exceptuando ciertos casos), sirviendo así de plantilla para los sucesivos tipos.
Por eso es de tipo abstracta, es decir somos nosotros la que le damos sentido.

Para java la clase abstracta, *llamada en ingles "resumen"*, es lo contrario a una clase concreta, nunca se van a crear instancias de ellas (como usar el comando **new**) solo sera una superclase de otras.

#### Métodos abstractos: 
 A su vez las clases abstractas tienen métodos abstractos:
 1. No tiene cuerpo
 2. Solo existen en clases abstract
 3. Deben estar sobreescritos en las subclases


***
