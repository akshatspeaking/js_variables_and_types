1. In code below "Mark" is a string. What is name?

```js
var name = "Mark";
```

Variable


2. Find the error if any

```js
  var product cost = 3.45;
```

var productCost = 3.45;


3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" //Right
  'Hello World" //Wrong
  "Hello World' //Wrong
  'Hello World' //Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man;  //Valid
var 1girl;   //Invalid
var woman3; //Valid
var -girl;  //Invalid
var blackDog; //Valid
var 42; //Inalid
var $42;  //Valid
var userName; //Valid
var x, y, z; //Valid
var x = 5, y = 6, z = 7; //Valid
var x = 5 + 10 + 2; //Valid
var user = "Tyrion"; "Arya"; "John"; //Invalid - will assign only "Tyrion" to user
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.

let amount1 = amount - 80;

// Define a new variable and store the value that is 200 more then the value of amount.

let amount2 = amount + 200;

// Define a new variable and store the value that is 4 times the value of amount.

let amount3 = amount*4;

// Define a new variable and store the reminder when the value of amount is  divided by 21.

let amount4 = amount%21;
```

## var, let and const

Write down the code or if there is any error write down the error.

```js
var user = "Sameer";
// Reassign the value of user to "Sam"

user = "Sam";

// Define a variable with name user with value "Irfan"

let user = "Irfan";

let number = 21;
// Reassign the value of number to 60

number = 60;

// Define another variable called number with the value of 100

let number = 100; //Invalid statement, since number already exists.

const username = "Admin";
// Reassign the value of username to "Arya"

Can not reassign value of const.

// Define a variable called username with value "John"

let username = "John";

```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark

let johnOlder = (johnAge>markAge);

// Check who is younger

let markYounger = (markAge<johnAge);

// Check if their age is equal

let ageEqual = (margAge==johnAge);

// Create a new variable and assign the age of john to new variable.

let johnAgeNew = johnAge;

// Check if john is equal to or greater then mark.

let check = (johnAge>=markAge);

// Check if john is less then or equal to mark.

let check = (johnAge<=markAge);

// Calculate the average age of john and mark and assign to a new variable.

let avg = (johnAge+markAge)/2;

```

Output of the following and why :

```js
let charactor = "Arya";
charactor = "John";
console.log(typeof charactor);

//String
//typeof returns type of variable, and charactor is a string. 

```

Output of the following and why :

```js
let charactor = "Arya";
console.log(typeof charactor);
charactor = 10;

//String
//console log is before reassignment of charactor. New value of charactor would be 10.

```

valid or not (why)

```js
null = 10;
console.log(null);

//Invalid assignment of "10" to null. Console log will output null.
//"null" is a reserved keyword, can not be set as variable name.
```
