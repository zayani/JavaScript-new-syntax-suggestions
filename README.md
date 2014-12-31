JavaScript-new-syntax-suggestions
=================================

### Variable property names (keys) in JavaScript Object Literal 

````js
var v="variable",
    obj = { ( v + "_key" ) : "value" };
    
console.log(v); // Object {variable_key: "value"}
````

> syntax 
````js
    obj = { (<expression>) : <value> }
````

The *expression* in the parentheses evaluated as the *property name* string.
