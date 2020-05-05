1. In code below "Mark" is a string. What is name?

```js
var name = "Mark";
```
name is varible


2. Find the error if any

```js
  var product cost = 3.45;
```
variable syntax is wrong.

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"    right
  'Hello World"    wrong
  "Hello World'    wrong
  'Hello World'    right
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man;  VALID
var 1girl; INVALID
var woman3;  VALID
var -girl;   INVALID
var blackDog; VALID
var 42;       INVALID
var $42;      VALID
var userName;  VALID
var x, y, z;   VALID
var x = 5, y = 6, z = 7; INVALID
var x = 5 + 10 + 2;  VALID
var user = "Tyrion"; "Arya"; "John";  INVALID
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var newAmount = amount - 80;
alert(newAmount);


// Define a new variable and store the value that is 200 more then the value of amount.
var newAmount = amount + 200;
alert(newAmount);


// Define a new variable and store the value that is 4 times the value of amount.
var newAmount = amount *4;
alert(newAmount);

// Define a new variable and store the reminder when the value of amount is  divided by 21.
var newAmount = amount % 21;
alert(newAmount);
```

## var, let and const

Write down the code or if there is any error write down the error.

```js
var user = "Sameer";
// Reassign the value of user to "Sam"
user = "Sam";
// Define a variable with name user with value "Irfan"
var userName = "Irfan";

let number = 21;
// Reassign the value of number to 60
number = 60;
// Define another variable called number with the value of 100
let number = 100;

const username = "Admin";
// Reassign the value of username to "Arya"
const value can't be changed.
// Define a variable called usernae with value "John"
let userName = "John";
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
if (johnAge > markAge){
    alert(johnAge);
} else {
    alert(markAge);
}

// Check who is younger
if (johnAge > markAge){
    alert(markAge);
} else {
    alert(johnAge);
}

// Check if their age is equal
if (johnAge == markAge){
    alert('their age is equal');
} else {
    alert("their age is not equal");
}
// Create a new variable and assign the age of john to new variable.
let samAge;
samAge = johnAge;

// Check if john is equal to or greater then mark.
if (johnAge >= markAge){
    alert(johnAge);
} else {
    alert(markAge);
}
// Check if john is less then or equal to mark.
if (johnAge >= markAge){
    alert(markAge);
} else {
    alert(johnAge);
}

// Calculate the average age of john and mark and assign to a new variable.
```
let avgAge = (johnAge+markAge)/2;
alert(avgAge);

Output of the following and why :

```js
let charactor = "Arya";
charactor = "John";
console.log(typeof charactor);  string
```

Output of the following and why :

```js
let charactor = "Arya";
console.log(typeof charactor);  string
charactor = 10;
```

valid or not (why)

```js
null = 10;
console.log(null);   not valid
```
