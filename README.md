<div align="center">
  <h2>JAVASRIPT AVANZADO</h2>
</div>

## Tabla de Contenido
- [Scope](#scope)

<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## Scope:

El Scope o ámbito es lo que define el tiempo de vida de una variable, en qué partes de nuestro código pueden ser usadas.

**Global Scope**
Variables disponibles de forma global se usa la palabra ```var```, son accesibles por todos los scripts que se cargan en la página. Aquí hay mucho riesgo de sobreescritura.

**Function Scope**
Variables declaradas dentro de una función sólo visibles dentro de ella misma (incluyendo los argumentos que se pasan a la función).

**Block Scope**
Variables definidas dentro de un bloque, por ejemplo variables declaradas dentro un loop while o for. Se usa **let** y **const** para declarar este tipo de variables.

**Module Scope**
Cuando se denota un script de tipo module con el atributo ```type="module``` las variables son limitadas al archivo en el que están declaradas.

Esto va a declarar que este archivo es un módulo. Esto no está en todos los navegadores pero sí en los más modernos. Los valores que teníamos escritos ahora no los vamos a poder leer en consola porque el module scope está limitando el alcance
