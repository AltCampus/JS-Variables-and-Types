1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```name is a variable acts like a container to store string "Mark".

2. Find the error if any
```js
  var product cost = 3.45;
``` cost is the error. y means we cannot define a variable name by using spaces if we need spaces we define with capital letter with out giving space.eg:naveenReddy.

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"  //right
  'Hello World"  //wrong
  "Hello World'  //wrong
  'Hello World'  //right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;   //valid
var 1girl;  //invalid
var woman3; //valid
var -girl;  //invalid
var blackDog; //valid
var 42;       //invalid
var $42;      //invalid
var userName; //valid
var x, y, z;  //valid
var x = 5, y = 6, z = 7; //valid
var x = 5 + 10 + 2; //valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var amount1 = amount-80;
console.log(amount1);
//2000

// Define a new variable and store the value that is 200 more then the value of amount.
var amount2 = amount1+200;
console.log(amount2);
//2200

// Define a new variable and store the value that is 4 times the value of amount.
var amount3 = amount2*4;
console.log(amount3);
//8800
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var amount4 = amount3/21;
console.log(amount4);
//419.04761904761904
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
  if(johnAge > markAge){
    console.log("johnAge is greater")
  }else{
    console.log("markAge is greater")
  }

ageVerifier()
//true

// Check who is younger
  if(markAge < johnAge){
    console.log("markAge is younger")
  }else{
    console.log("John is older")
  }

//true
// Check if their age is equal
 if(johnAge == markAge){
   console.log("their age is equal")
 }else{
   console.log("their age is not equal")
 }
// Create a new variable and assign the age of john to new variable.
let naveenReddy = 45;
// Check if john is equal to or greater then mark.
if(johnAge >= markAge){
console.log("their age is greater than or equal")
}
// Check if john is less then or equal to mark.
if(johnAge <= markAge){
console.log("their age is greater than or equal")
}

// Calculate the average age of john and mark and assign to a new variable.
```
var average=johnAge+markAge/2;
console.log(average);
//62.5