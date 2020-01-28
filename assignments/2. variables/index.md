1. In code below "Mark" is a string. What is name?

```js
var name = "Mark";
variable name
```

2. Find the error if any

````js
  var product cost = 3.45;
```"cost" is Unexpected identifier

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"
  Right

  'Hello World"
  Worng

  "Hello World'
  Worng

  'Hello World'
  Right
````

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man;  //Valid
var 1girl;  // Invalid
var woman3;  // Valid
var -girl;  // Invalid
var blackDog;  // valid
var 42; // Invalid
var $42;  // Valid
var userName;  // Valid
var x, y, z; // valid
var x = 5, y = 6, z = 7; // valid
var x = 5 + 10 + 2;   // Valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var a = 80;
alert(amount - a);

// Define a new variable and store the value that is 200 more then the value of amount.
var b = 200;
alert(amount + b);

// Define a new variable and store the value that is 4 times the value of amount.
var c = 4;
alert(amount * c);

// Define a new variable and store the reminder when the value of amount is  divided by 21.
var d = 21;
alert(amount / d);
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
var johnAge = 45;
var markAge = 35;
var age = johnAge > markAge ? `john is older` : `mark is older`;
alert(age);
// Check who is younger
var age = johnAge < markAge ? `john is younger` : `mark is younger`;
alert(age);
// Check if their age is equal
var age = johnAge == markAge ? `Equal age` : `Not equal age`;
alert(age);

// Create a new variable and assign the age of john to new variable.
var devidAge = 45;
// Check if john is equal to or greater then mark.
var age = johnAge >= markAge ? `greater ` : `less`;
alert(age);

// Check if john is less then or equal to mark.
var age = johnAge <= markAge ? `less ` : ` greater`;
alert(age);

// Calculate the average age of john and mark and assign to a new variable.

alert((johnAge + markAge) / 2);
```
