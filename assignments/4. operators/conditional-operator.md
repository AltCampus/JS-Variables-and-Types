## If Statement

1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

⛑ Rule
_ [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
⚡️ Operations
_ [ ] Add
_ [ ] Sub
_ [ ] Mul \*
[ ] Div

```js
let a = Number(prompt("first value"));
let s = Number(prompt("second value"));
let operator = prompt("enter +, -, _, /");
if (operator == "+") alert(a + s);
if (operator == "-") alert(a - s);
if (operator == "_")
  alert(aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\ * s);
if (operator == "/") alert(a / s);
```

2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`

```js
var firstName = "John";
var status = "single";
// Your code goes here
if ((status = "single")) {
  console.log("john is single");
} else {
  console.log("hohn is married");
}
```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.

```js
// your code goes here
var a = prompt("first intiger");
var b = prompt("second intiger");
if (a > b) {
  alert("a is greater");
} else {
  alert("b is greater");
}
```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here
var a = prompt("first intiger");
var b = prompt("second intiger");
var c = prompt("third integer");
alert(a * b * c);
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.

- [ ] ONE, if `number` is equal to 1.
- [ ] TWO, if `number` is equal to 2.
- [ ] THREE, if `number` is equal to 3.
- [ ] FOUR, if `number` is equal to 4.
- [ ] FIVE, if `number` is equal to 5.
- [ ] SIX, if `number` is equal to 6.
- [ ] SEVEN, if `number` is equal to 7.
- [ ] EIGHT, if `number` is equal to 8.
- [ ] NINE, if `number` is equal to 9.
- [ ] PLEASE TRY AGAIN, if is none of the above.

```js
// Your code goes here

var number = prompt("Enter number");
switch (number) {
  case "1":
    alert("ONE");
    break;
  case "2":
    alert("TWO");
    break;
  case "3":
    alert("THREE");
    break;
  case "4":
    alert("FOUR");
    break;
  case "5":
    alert("FIVE");
    break;
  case "6":
    alert("SIX");
    break;
  case "7":
    alert("SEVEN");
    break;
  case "8":
    alert("EIGHT");
    break;
  case "9":
    alert("NINE");
    break;
  default:
    alert("Please try again");
    break;
}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.

- [ ] `AA` if `marks` is greater than 90.
- [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
- [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
- [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
- [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
- [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
- [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
- [ ] `FF` if `marks` is less than or equal to 30

```js
// Your code goes here

var mark = prompt("Enter mark");
switch (true) {
  case mark > 90:
    alert("AA");
    break;
  case mark > 80 && mark <= 90:
    alert("AB");
    break;
  case "mark > 70 && mark <= 80":
    alert("BB");
    break;
   case "mark > 60 && mark <= 70":
    alert("BC");
    break;
  case mark > 50 && mark <= 60:
    alert("CC");
    break;
  case "mark > 40 && mark <= 50":
    alert("CD");
    break;
    case "mark > 30 && mark <= 40":
    alert("DD");
    break;
    case "mark >= 30 :
    alert("FF");
    break;
  default:
    alert("Please try again");
    break;
}
```
