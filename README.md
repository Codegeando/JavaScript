

Introducción a JavaScript
===================
[TOC]

Variables y asignación
-------------
Las variables en JavaScript son declaradas antes de ser usadas:
```
var x; // Declaracion de variable
```
Se puede declarar una variable y asignarle un varlor:
```
var x = 20; //
```
Ademas se puede asignar un valor a una variable existente:
```
x = 25;
```
**Operadores de asignacion compuestos**
```
a + = 1;
a = a + 1;
```
Identificadores y Palabras reservadas
-------------
Un identificador es un nombre al cual se hace referencia a una variable, constante, función u objeto. Cuenta con algunas reglas que son: 

 - Secuencia de letras [a-z-A-Z] y digitos [0-9].
 - El primer caracter debe ser cualquier letra, un signo dolar ($) o un guion bajo (_).
```
var goku;
var _Veget4;
var $g0h4n;
```

|Palabras  | Reservadas       |       |     |
| ------------------ |:------:|:-----:| :---:|
| arguments | break  | case | catch |
| class| const| continue| debugger |
| default| delete| do | else|
| enum| export|extends |false |
| finally| for| function | if|
| implements| import|in |instanceof |
| interface| let| new |null |
| package| private|protected |public |
| return | static|super |swicth |
| this| throw|true |try |
| typeof| var|void |while |

Los siguientes identificadores, no son palabras reservadas, pero debe de tratarlas como si lo fueran.
|  			|
| :-------: |
| Infinity  |
| NaN       |
|undefined  |

Comentarios
-------------
JavaScript posee dos formas en la que se pueden realizar comentarios, comentarios una sola linea y multilineas.
El comentario de una sola linea inicia con // .
```
var z; // comentario de una sola linea
```
Los comentarios multilineas se delimitan con /* y */
```
/* Este es 
	un comentario de 
	varias lineas 
*/
```

