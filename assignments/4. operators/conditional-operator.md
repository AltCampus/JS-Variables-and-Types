## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div
```js

  let int1 = +prompt("enter the 1st number");
  let int2 = +prompt("enter the 2nd number");
  let operator = prompt("enter the operator,+ , - ,* ,% , etc");
  if (operator === `+`){
    alert(`addition is ${int1 + int2}`);
  } else if (operator === `-`) {
    alert(` substraction is ${int1 - int2}`);
  } else if (operator === `*`) {
    alert(`multiplication is${int1 * int2}`);
  } else if (operator === `%`) {
    alert(` reminder is ${int1 % int2}`);
  } else {
    alert("invalid operator");
  }

```

2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
// Your code goes here
var firstName = 'John';
var status;
alert(status)
  if(status="single"){
    alert("john is single")
    }
    else{
      alert("john is married")
    }

```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here
let input1 = prompt("Enter First Integer");
  let input2 = prompt("Enter Second Integer");

  if(input1 > input2){
	  alert("${input1} is greater");
  }
  else if (input1 < input2) {
		alert ("${input2} is greater");
	}
	else if (input1 = input2)
	{
		alert ("Both Integers are same");
	}
	else {
		alert ("Invalid input");
	}
```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here
let integer1 = +prompt("Enter First Integer");
let integer2 = +prompt("Enter First Integer");
let operator = prompt("enter the operator,+ , - ,* ,% , etc");
if (operator === "+"){
	alert("Addition is ${integer1 + integer2}");
} else if (operator === "-") {
	alert("Substraction is ${integer1 - integer2}");
} else if (operator === "*") {
	alert("Multiplication is${integer1 * integer2}");
} else if (operator === "%") {
	alert("Reminder is ${integer1 % integer2}");
} else {
	alert("Invalid operator");
}
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
let input = +prompt("enter an integer");
let ONE = 1;
let TWO = 2;
let THREE = 3;
let FOUR = 4;
let FIVE = 5;
let SIX = 6;
let SEVEN = 7;
let EIGHT = 8;
let NINE = 9;

switch(input) {
  case ONE:
  alert("Number is ${input}");
  break ;
  case TWO:
  alert("Number is ${input}");
  break ;
  case THREE:
  alert("Number is ${input}");
  break;
  case FOUR:
  alert("Number is ${input}");
  break;
  case FIVE:
  alert("Number is ${input}");
  case SIX:
  alert("Number is ${input}");
  case SEVEN:
  alert("Number is ${input}");
  case EIGHT:
  alert("Number is ${input}");
  case NINE:
  alert("Number is ${input}");
  default:
  alert("Try again");
}

```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here
let marks = +prompt("Enter your marks in numbers ");
switch(true) {
	case (marks > 90):
	alert("AA");
	break;
	case (marks > 80 && marks <= 90):
	alert("AB");
	break;
	case (marks > 70 && marks <= 80):
	alert("BB");
	break;
	case (marks > 60 && marks <= 70):
	alert("BC");
	break;
	case (marks > 50 && marks <= 60):
	alert("CC");
	break;
	case (marks > 40 && marks <= 50):
	alert("CD");
	break;
	case (marks > 30 && marks <= 40):
	alert("DD");
	break;
	case (marks <= 30):
	alert("FF");
	break;
	default :
	alert("Default");
}
```
