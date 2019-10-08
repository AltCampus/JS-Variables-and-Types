1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```

2. Find the error if any
```js
  var productCost = 3.45;
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"
  'Hello World" //wrong
  "Hello World' //wrong 
  'Hello World'
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;  //valid
var 1girl; //invalid
var woman3; //valid
var -girl; //invalid
var blackDog; //valid
var 42; //invalid
var $42; //valid
var userName; //valid
var x, y, z; //valid
var x = 5, y = 6, z = 7;  //valid
var x = 5 + 10 + 2; //valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var x;
x = amount - 80;
alert(x);

// Define a new variable and store the value that is 200 more then the value of amount.
var x;
x = amount + 200;
alert(x);

// Define a new variable and store the value that is 4 times the value of amount.
var x;
x = 4 * amount ;
alert(x);

// Define a new variable and store the reminder when the value of amount is  divided by 21.
var x;
x = amount % 21;
alert(x);


```
Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark
  johnAge>markAge && alert('johnage is older') //false
// Check who is younger
  markAge<johnAge && alert('mark is younger') //true
// Check if their age is equal
  markAge == johnAge && alert('age is not equal') //false
// Create a new variable and assign the age of john to new variable.
  var x;
  x = johnAge;
  alert(x);   //x=45
// Check if john is equal to or greater then mark.
 johnAge == markAge;    //false
 johnAge > markAge;     //true 
// Check if john is less then or equal to mark.
 johnAge < markAge;    //false
 johnAge == markAge;     //false
// Calculate the average age of john and mark and assign to a new variable.
 var x;
 x = (johnAge+markAge)/2;
```