<div align="center">
  <h2>JavaScript Avanzado</h2>
</div>

## Tabla de Contenido
- [Entendiendo-avascript](#Entendiendo-JavaScript)
- [Syntax-Parser](#Syntax-Parser)
- [Scope](#scope)
 
<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## Entendiendo JavaScript: (Single threaded y Sincronico)

Sincrono, de un solo proceso y un solo hilo.

threaded => (es una serie de instrucciones).

<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## Syntax Parser

Es un Proceso automatico que validad mi codigo.  

<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## Scope:

El Scope o ámbito es lo que define el tiempo de vida de una variable, en qué partes de nuestro código pueden ser usadas.

**Global Scope:**
Variables disponibles de forma global se usa la palabra ```var```, son accesibles por todos los scripts que se cargan en la página. OJO:(Aquí hay mucho riesgo de sobreescritura).
//Toda variable que declaremos fuera de una función o un bloque. Pertenece al  Scope Global.

**Scope Local**

**-->Function Scope**
Las Variables declaradas dentro de una función, sólo son visibles dentro de ella misma (incluyendo los argumentos que se pasan a la función).
//Aceder a las variables dentro del cuerpo de la funcion y no fuera de ellas.

**-->Block Scope:**
Las Variables definidas dentro de un bloque => (Toda porción de codigo que esta escrita entre llaves), por ejemplo variables declaradas dentro un loop while o for. Se usa **let** y **const** para declarar este tipo de variables.

**Module Scope**
Cuando se denota un script de tipo module con el atributo ```type="module``` las variables son limitadas al archivo en el que están declaradas.
Esto va a declarar que este archivo es un módulo. Esto no está en todos los navegadores pero sí en los más modernos. Los valores que teníamos escritos ahora no los vamos a poder leer en consola, porque el module scope está limitando el alcance.
