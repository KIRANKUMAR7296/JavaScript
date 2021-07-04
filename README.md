# Javascript

Programming language of the `Web`.

Javascript can change `HTML` content.

Javascript accepts both double quotes `""` and single quotes `''`.

### Data Types
```javascript
var name = "Kirankumar";            # String
var age = 25;                       # Number | Integer
var weight = 70.5;                  # Number | Float
var ismale = true;                  # Boolean
var x = null;             
var array = [5, "Hi", true, 7.7];   # Object
```

### What is Hoisting ?
- `Default` bahaviour of Javascript where all the `Variables` and `Functions` declarations are moved on the top. 

### Difference between "==" and "==="

```javascript
var x = 2;
var y = "2";
`x == y`    # Return True since x and y are same.
`x === y`   # Return False since typeof x is "Number" and typeof y is "String".
```
### Implicit Type Coercion in Javascript
- `Automatic` conversion of value from one data type to another.

```javascript
var x = 3;
var y = "3";
x + y         Output : "33"

var x = 25
var y = "Hi"
x + y         Output : "25Hi"
```
