Patron Modular
===================

Funciones autoejecutables
-------------
Estas funciones tienen la facultad, que una vez declaradas, se llaman a si mismas.
```javascript
(function(){ /* sentencias */ })();
```
Analizando...
Declaracion de una funcion y su llamado:

```javascript
function myfn(){
	console.log('Hello World!!');
}
myfn(); // Llama a la función.
(myfn)(); // Autoejecuta la función.
```

Ejemplo con Funcion anónima, usada convencionalmente por la librería JQuery.

```javascript
(function(){
	console.log("Mi funcion anonima");
})();
```

Patron Modular
-------------
Es considerado un Patrón de Diseño, que nos ofrece la posibilidad de simular propiedades y métodos privados (convención: Programación Orientada Objetos). 

Module Pattern, se implementa con la creacion de una funcion anónima autoejecutable que retorna un objeto literal.

```javascript
//namespace
var myModule = {};
//Definción de mi modulo.
myModule = (function(){
	//variables privadas || Propiedades
    var p1;
    var p2;
    
    // funciones privadas || Metodos
    function aPrivatemethod(){
    	// ...
    }
    
    function bPrivatemethod(){
    	// ...
    }
    
    // retorna objeto literal
    return {
    	p1 : p1,
        publicMethod : function(){
        	// ...
        },
        otherPublicMethod : function(){
        	// ...
        }
    }
    
})();
```