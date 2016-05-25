

Introducción a JavaScript
===================

Variables y asignación
-------------
Las variables en JavaScript son declaradas antes de ser usadas:
```javascript
var x; // Declaracion de variable
```
Se puede declarar una variable y asignarle un varlor:
```javascript
var x = 20; //
```
Ademas se puede asignar un valor a una variable existente:
```javascript
x = 25;
```
**Operadores de asignacion compuestos**
```javascript
a + = 1;
a = a + 1;
```
Identificadores y Palabras reservadas
-------------
Un identificador es un nombre al cual se hace referencia a una variable, constante, función u objeto. Cuenta con algunas reglas que son: 

 - Secuencia de letras [a-z-A-Z] y digitos [0-9].
 - El primer caracter debe ser cualquier letra, un signo dolar ($) o un guion bajo (_).
```javascript
var goku;
var _Veget4;
var $g0h4n;
```

|Palabras Reservadas  |       |       |     |
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

|  Palabras no Reservadas |
| :---------: |
| Infinity  |
| NaN       |
|undefined  |

Comentarios
-------------
JavaScript posee dos formas en la que se pueden realizar comentarios, comentarios una sola linea y multilineas.
El comentario de una sola linea inicia con // .
```javascript
var z; // comentario de una sola linea
```
Los comentarios multilineas se delimitan con /* y */
```javascript`
/* Este es 
	un comentario de 
	varias lineas 
*/
```
Tipos de Variables
-------------
**Primitivos**
Los valores primitivos son: booleanos, numeros, cadenas, null, undefined
```javascript
var num = 1;
var cad = 'Goku';
var band = false;
console.log(num,cad,band);
```
	* Booleanos: true o false.
	* Numeros : enteros y decimales [0-9].
    * Cadenas : 'abc', '4b3' [a-z-A-z-0-9].
    * No values : indefinido, nulo [null, undefined].

Arrays
-------------
Suelen ser llamados vectores, matrices e incluso arreglos. 
Es una coleccion de variables, que pueden ser de un mismo tipo o diferentes.
```javascript
var week = ['Lunes','Martes','Miercoles','Jueves','Viernes','Sabado','Domingo'];
console.log(week);
console.log(week[2]);
```

Objetos
-------------
Es una entidad independiente con propiedades y tipos.

```javascript
var person = {
	firts_name : 'Jesus',
    last_name : 'Moreno',
    job : 'Developer'
};
console.log(person);
```
Operadores
-------------
Los operadores nos permiten manipular el valor de las variables, mediante operaciones matemáticas (suma, resta, multiplicacion y division), comparación de valores ademas de operadores lógicos.

**Incremento y decremento**

```javascript
var num = 10;
num++; // ++num | num = num + 1;
num--; // --num | num = num - 1;
```
**Operadores Matemáticos**

```javascript
var num1 = 10;
var num2 = 5;
sum = num1 + num2; // Suma
sub = num1 - num2; // Resta
mult = num1 * num2; // Multiplicación
div = num1 / num2; // División
```
**Operadores Lógicos**

* Negación

```javascript
var band = true;
console.log(!band);
```

* AND

```javascript
var band1 = true;
var band2 = false;
var res = band1 && band2;
console.log(res);
```

* OR

```javascript
var band1 = true;
var band2 = false;
var res = band1 || band2;
console.log(res);
```

**Operadores Relacionales**

```javascript
var num1 = 10;
var num2 = 5;
var num3 = 5;
res = num1 > num2; // res = true
res = num1 < num2; // res = false
res = num1 >= num2; // res = true
res = num1 <= num2; // res = false
res = num2 == num3; // res = true
res = num2 != num3; // res = false
```

Estructuras de Control de Flujo
-------------
Condicionales y bucles en JavaScript.

**Condicionales**
