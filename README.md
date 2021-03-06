<div align="center">
  <h2>JavaScript Avanzado</h2>
</div>

## Tabla de Contenido
- [Entendiendo-avascript](#Entendiendo-JavaScript)
- [Syntax-Parser](#Syntax-Parser)
- [Lexical-environment](#Lexical-environment)
- [Scope](#scope)
 
<div align="right">
  <small><a href="#tabla-de-contenido">馃　 volver al inicio</a></small>
</div>

## Entendiendo JavaScript: (Single threaded y Sincronico)

Sincrono, de un solo proceso y un solo hilo.

threaded => (es una serie de instrucciones).

<div align="right">
  <small><a href="#tabla-de-contenido">馃　 volver al inicio</a></small>
</div>

## Syntax Parser:

Es un Proceso automatico que validad mi codigo.  

<div align="right">
  <small><a href="#tabla-de-contenido">馃　 volver al inicio</a></small>
</div>

## Lexical environment:

Me dice que variables hay dentro de cada espacio o contexto de ejecucion.

<div align="right">
  <small><a href="#tabla-de-contenido">馃　 volver al inicio</a></small>
</div>

## Scope:

El Scope o 谩mbito es lo que define el tiempo de vida de una variable, en qu茅 partes de nuestro c贸digo pueden ser usadas.

**Global Scope:**
Variables disponibles de forma global se usa la palabra ```var```, son accesibles por todos los scripts que se cargan en la p谩gina. OJO:(Aqu铆 hay mucho riesgo de sobreescritura).
//Toda variable que declaremos fuera de una funci贸n o un bloque. Pertenece al  Scope Global.

**Scope Local**

**-->Function Scope**
Las Variables declaradas dentro de una funci贸n, s贸lo son visibles dentro de ella misma (incluyendo los argumentos que se pasan a la funci贸n).
//Aceder a las variables dentro del cuerpo de la funcion y no fuera de ellas.

**-->Block Scope:**
Las Variables definidas dentro de un bloque => (Toda porci贸n de codigo que esta escrita entre llaves), por ejemplo variables declaradas dentro un loop while o for. Se usa **let** y **const** para declarar este tipo de variables.

**Module Scope**
Cuando se denota un script de tipo module con el atributo ```type="module``` las variables son limitadas al archivo en el que est谩n declaradas.
Esto va a declarar que este archivo es un m贸dulo. Esto no est谩 en todos los navegadores pero s铆 en los m谩s modernos. Los valores que ten铆amos escritos ahora no los vamos a poder leer en consola, porque el module scope est谩 limitando el alcance.
