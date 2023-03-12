# **Basic Javascript**



This repository contains my solutions to the freecodecamp JavaScript Algorithms and Data Structures exercises. 
Completed to improve muscle memory in coding. This is learning by doing. 
- [x] Learn and master JavaScript
- [x] Learn and master Markdown
- [x] Learn and master Git/GitHub


---


### Exercise 1: Comment Your JavaScript Code
Try creating one of each type of comment.

```
// I-type ang double forward slash para magdagdag ng inline comment.

/* Gayahin ang format na ito 
kung kinakailangan magdagdag ng
mahabang multi-line comment */
```


### Exercise 2: Declare JavaScript Variables
Use the var keyword to create a variable called myName.

```
var myName;
```


### Exercise 3: Storing Values with the Assignment Operator
Assign the value 7 to variable a.

```
// Setup
var a;

// Only change code below this line
a = 7;
```


### Exercise 4: Assigning the Value of One Variable to Another
Assign the contents of a to variable b.

```
// Setup
var a;
a = 7;
var b;

// Only change code below this line
b = a
```


### Exercise 5: Initializing Variables with the Assignment Operator
Define a variable a with var and initialize it to a value of 9

```
var a = 9;
```


### Exercise 6: Declare String Variables

Create two new string variables: myFirstName and myLastName and assign them the values of your first and last name, respectively.

```
var myFirstName = "John";
var myLastName = "Javier";
```
*We declare a variable with the keyword "var" in JavaScript, unlike in Python we do not. And end each with a ";". "let" and "const" are used instead of "var" in modern JavaScript development, ref: ES6.*


### Exercise 7: Understanding Unitiatialized Variables
Initialize the three variables a, b, and c with 5, 10, and "I am a" respectively so that they will not be undefined.

```
// Only change code below this line
var a = 5;
var b = 10;
var c = "I am a";
// Only change code above this line

a = a + 1;
b = b + 5;
c = c + " String!";
```


### Exercise 8: Understanding Case Sensitivity in Variables
Modify the existing declarations and assignments so their names use camelCase. Do not create any new variables.

```
// Variable declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Variable assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```


### Exercise 9: Explore Differences Between the var and let Keywords
Update the code so it only uses the let keyword.

```
let catName = "Oliver";
let catSound = "Meow!";
```


### Exercise 10: Declare a Read-Only Variable with the const Keyword
Change the code so that all variables are declared using let or const. Use let when you want the variable to change, and const when you want the variable to remain constant. Also, rename variables declared with const to conform to common practices. Do not change the strings assigned to the variables.

```
const FCC = "freeCodeCamp"; // Change this line
let fact = "is cool!"; // Change this line
fact = "is awesome!";
console.log(FCC, fact); // Change this line
```

*Use const to declare read-only variables, that cannot be reassigned, unlike that of "let" and "var"* 


### Exercise 11: Add Two Numbers with JavaScript
Change the 0 so that sum will equal 20. 

```
const sum = 10 + 10;
```


### Exercise 12: Subtract One Number from Another with JavaScript
Change the 0 so the difference is 12.

```
const difference = 45 - 33;
```


### Exercise 13: Multiply Two Numbers with JavaScript
Change the 0 so that the product will equal 80. 

```
const product = 8 * 10;
```


### Exercise 14: Divide One Number by Another with JavaScript
Change the 0 so that the quotient is equal to 2. 

```
const quotient = 66/33;
```


### Exercise 15: Increment a Number with JavaScript
Change the code to use the ++ operator on my myVar. 

```
let myVar = 87;

// Only change code below this line
myVar++;
```


### Exercise 16: Decrement a Number with JavaScript
Change the code to use -- operator on myVar

```
let myVar =11;
myVar--;
```


### Exercise 17: Create Decimal Numbers with JavaScript
Create a variable myDecimal and give it a decimal value with a fractional part (e.g. 5.7)

```
const ourDecimal = 5.7;

// Only change code below this line

const myDecimal = 3.14;
```


### Exercise 18: Multiply Two Decimals with JavaScript
Change the 0.0 so that product will equal 5.0.

```
const product =2.0 * 2.5; // Change this line
```


### Exercise 19: Divide One Decimal by Another with JavaScript
Change the 0.0 so that the quotient will equal to 2.2.

```
const quotient = 4.4 / 2.0; // Change this line
```


### Exercise 20: Finding a Remainder in JavaScript

**Good to know**
A number can be checked either even or odd by checking the remainer of the division of the number by 2. 
> 17 % 2 = 1 (17 is Odd)

> 48 % 2 = 0 (48 is Even)

Set remainder equal to the remainder of 11 divided by 3 using the remainder (%) operator.

```
const remainder = 11 % 3;
```


### Exercise 21: Compound Assignment With Augmented Addition
Convert the assignments for a, b, and c to use the += operator. 

```
let a = 3;
let b = 17;
let c = 12;

// Only change code below this line
a += 12;
b += 9;
c += 7;
```


### Exercise 22: Compound Assignment With Augmented Subtraction
Convert the assignments for a, b, and c to use the -= operator. 

```
let a = 11;
let b = 9;
let c = 3;

// Only change code below this line
a -= 6;
b -= 15;
c -= 1;
```


### Exercise 23: Compound Assignment With Augmented Multiplication
Convert the assignments for a, b, and c to use the *= operator.
```
let a = 5;
let b = 12;
let c = 4.6;

// Only change code below this line
a *= 5;
b *= 3;
c *= 10;
```


### Exercise 24: Compound Assignment With Augmented Division
Convert the assignments for a, b, and c to use the /= operator.

```
let a = 48;
let b = 108;
let c = 33;

// Only change code below this line
a /= 12; //should equal 4
b /= 4; //should equal 27
c /=  11; // should equal 3
```


### Exercise 25: Escaping Literal Quotes in Strings
Use backslashes to assign a string to the myStr variable so that if you were to print it to the console, you would see:

> I am a "double quoted" string inside "double quotes".

```
const myStr ="I am a \"double quoted\" string inside \"double quotes\"."; // Change this line
```


### Exercise 26: Quoting Strings with Single Quotes
Change the provided string to a string with single quotes at the beginning and end and no escape characters.

Right now, the <a> tag in the string uses double quotes everywhere. You will need to change the outer quotes to single quotes so you can remove the escape characters.

```
const myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```


### Exercise 27: Escape Sequence in Strings
---
|**Good to Know**|Code|Output|
|---|---|---|
||\\'|single quote|
||\\"|double quote|
||\\\\ |backslash|
||\\n|newline|
||\\t|tab|
||\\r|carriage return|
||\\b|word boundary|
||\\f|form feed|
--- 

Assign the following three lines of text into the single variable myStr using escape sequences.
```
FirstLine
    \SecondLine
 ThirdLine
```

```
const myStr = "FirstLine\n\t\\SecondLine\nThirdLine"; // Change this line
```


### Exercise 28: Concatenating Strings with Plus Operator
 Build myStr from the strings This is the start. and This is the end. using the + operator. Be sure to include a space between the two strings.
```
const myStr ="This is the start. "+"This is the end.";
```


### Exercise 29: Concatenating Strings with the Plus Equals Operator
Build myStr over several lines by concatenating these two strings: This is the first sentence. and This is the second sentence. using the += operator. Use the += operator similar to how it is shown in the example and be sure to include a space between the two strings. Start by assigning the first string to myStr, then add on the second string.
```
let myStr = "This is the first sentence. ";
myStr += "This is the second sentence."
```


### Exercise 30: Constructing Strings with Variables
Set myName to a string equal to your name and build myStr with myName between the strings My name is and and I am well!

```
// Only change code below this line
const myName = "Juanito";
const myStr = "My name is "+ myName + " and I am well!";
```


### Exercise 31: Appending Variables to Strings
Set someAdjective to a string of at least 3 characters and append it to myStr using the += operator.

```
// Change code below this line
const someAdjective = "adventure!";
let myStr = "Learning to code is ";
myStr += someAdjective;
```


### Exercise 32: Find the Length of a String
Use the .length property to set lastNameLength to the number of characters in lastName.
```
// Setup
let lastNameLength = 0;
const lastName = "Lovelace";

// Only change code below this line
lastNameLength = lastName.length; //<should be equal to eight
```


### Exercise 33: Use Bracket Notation to Find the First Character in a String
Use bracket notation to find the first character in the lastName variable and assign it to firstLetterOfLastName.
```
// Setup
let firstLetterOfLastName = "";
const lastName = "Lovelace";

// Only change code below this line
firstLetterOfLastName = lastName[0]; // Change this line
```


### Exercise 34: Understand String Immutability

**Good to know!** *String values are immutable, which means that they they cannot be altered once created, but they can be re-assigned with a new value.*

Correct the assignment to myStr so it contains the string value of Hello World using the approach shown in the example above.
```
// Setup
let myStr = "Jello World";

// Only change code below this line
myStr = "Hello World"; // Change this line
// Only change code above this line
```


### Exercise 35: Use Bracket Notation to Find the Nth Character in a String

Let's try to set thirdLetterOfLastName to equal the third letter of the lastName variable using bracket notation.
```
// Setup
const lastName = "Lovelace";

// Only change code below this line
const thirdLetterOfLastName = lastName[2]; // Change this line
```


### Exercise 36: Use Bracket Notation to Find the Last Character in a String
```
Use bracket notation to find the last character in the lastName variable. 
// Setup
const lastName = "Lovelace";

// Only change code below this line
const lastLetterOfLastName = lastName[lastName.length -1]; // Change this line
```


### Exercise 37: Use Bracket Notation to Find the Nth-to-Last Character in a String
Use bracket notation to find the second-to-last character in the lastName string.
```
// Setup
const lastName = "Lovelace";

// Only change code below this line
const secondToLastLetterOfLastName = lastName[lastName.length -2]; // Change this line
```


### Exercise 38: Word Blanks
In this challenge, we provide you with a noun, a verb, an adjective and an adverb. You need to form a complete sentence using words of your choice, along with the words we provide.

You will need to use the string concatenation operator + to build a new string, using the provided variables: myNoun, myAdjective, myVerb, and myAdverb. You will then assign the formed string to the wordBlanks variable. You should not change the words assigned to the variables.

You will also need to account for spaces in your string, so that the final sentence has spaces between all the words. The result should be a complete sentence.

```
const myNoun = "dog";
const myAdjective = "big";
const myVerb = "ran";
const myAdverb = "quickly";

// Only change code below this line
const wordBlanks = "My " + myNoun + " is " + myAdjective + ". He just " + myVerb + " so " + myAdverb + " to me now."; // Change this line
// Only change code above this line
```


### Exercise 39: Store Multiple Values in one Variable using JavaScript Arrays
Modify the new array myArray so that it contains both a string and a number (in that order).
```
const myArray = ["one", 1, "two", 2, "three", 3];
```


### Exercise 40: Nest one Array within Another Array
Create a nested array called myArray.

```
const myArray = [["one", 1],["two", 2],["three", 3]];
```


### Exercise 41: Access Array Data with Indexes
Create a variable called myData and set it to equal the first value of myArray using bracket notation.
```
const myArray = [50, 60, 70];
const myData =myArray[0];
```


### Exercise 42: Modify Array Data With Indexes
**Good to know!** *Entries of arrays are mutable and can be changed freely.*
```
// Setup
const myArray = [18, 64, 99];

// Only change code below this line
myArray[0] = 45;
```


### Exercise 43: Access Multi-Dimensional Arrays With Indexes
Using bracket notation select an element from myArray such that myData is equal to 8.
```
const myArray = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14],
];

const myData = myArray[2][1];
```


### Exercise 44: Manipulate Arrays With push Method
Push ["dog", 3] onto the end of the myArray variable.

```// Setup
const myArray = [["John", 23], ["cat", 2]];

// Only change code below this line
myArray.push(["dog",3]);
```


### Exercise 45: Manipulate Arrays With pop Method
**Good to know!** *.push is to add a value at the end of the array, while .pop is to change/replace the end of the array with a new value.*

Use the .pop() function to remove the last item from myArray and assign the popped off value to a new variable, removedFromMyArray.

const myArray = [["John", 23], ["cat", 2]];
```
// Setup
const myArray = [["John", 23], ["cat", 2]];

// Only change code below this line
const removedFromMyArray = myArray.pop();
```


### Exercise 46: Manipulate Arrays With shift Method
Use the .shift() function to remove the first item from myArray and assign the "shifted off" value to a new variable, removedFromMyArray.

```
// Setup
const myArray = [["John", 23], ["dog", 3]];

// Only change code below this line
const removedFromMyArray = myArray.shift();
```


### Exercise 47: Manipulate Arrays With unshift Method
**Good to know!** *.unshift method works like the .push, but instead replaces the element at the beginning of the array.*

Add ["Paul", 35] to the beginning of the myArray variable using unshift().

```
// Setup
const myArray = [["John", 23], ["dog", 3]];
myArray.shift();

// Only change code below this line
myArray.unshift(["Paul",35]); //
```


### Exercise 48: Shopping List
Create a shopping list in the variable myList. The list should be a multi-dimensional array containing several sub-arrays.

```
const myList =[["shampoo", 1,],["conditioner",2],["soap", 6], ["sponge", 3], ["detergent soap",1]];
```


### Exercise 49: Write Reusable JavaScript with Function
1. Create a function called reusableFunction which prints the string Hi World to the dev console.
2. Call the function.

```
function reusableFunction() {
  console.log("Hi World")
}

reusableFunction()
```


### Exercise 50: Passing Values to Functions with Arguments

1. Create a function called functionWithArgs that accepts two arguments and outputs their sum to the dev console.
2. Call the function with two numbers as arguments.

```
function functionWithArgs(arg1,arg2){
  console.log(arg1 + arg2);
}

functionWithArgs(4,5)
```


### Exercise 51: Return a Value From a Function with Return

Create a function timesFive that accepts one argument, multiplies it by 5, and returns the new value.
```
function timesFive(num) {
  return num * 5 ;
}

const answer = timesFive(9);
```


### Exercise 52: Global Scope and Functions

Using let or const, declare a global variable named myGlobal outside of any function. Initialize it with a value of 10.

Inside function fun1, assign 5 to oopsGlobal without using the var, let or const keywords.

```
// Declare the myGlobal variable below this line
const myGlobal = 10

function fun1() {
  // Assign 5 to oopsGlobal here
  oopsGlobal = 5;
}

// Only change code above this line

function fun2() {
  let output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
```


### Exercise 53: Local Scope and Functions

The editor has two console.logs to help you see what is happening. Check the console as you code to see how it changes. Declare a local variable myVar inside myLocalScope and run the tests.

```
function myLocalScope() {
  // Only change code below this line
  const myVar = 0;
  console.log('inside myLocalScope', myVar);
}
myLocalScope(myVar);

// Run and check the console
// myVar is not defined outside of myLocalScope
console.log('outside myLocalScope', myVar);
```


### Exercise 54: Global vs Local Scope in Functions

Add a local variable to myOutfit function to override the value of outerWear with the string sweater.
```
// Setup
const outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
  const outerWear = "sweater";
  // Only change code above this line
  return outerWear;
}

myOutfit();
```


### Exercise 55: Understanding Undefined Value returned from a Function

Create a function addFive without any arguments. This function adds 5 to the sum variable, but its returned value is undefined.

```
// Setup
let sum = 0;

function addThree() {
  sum = sum + 3;
}

// Only change code below this line
function addFive() {
  sum = sum + 5; // or sum += 5
}
// Only change code above this line

addThree();
addFive();
```


### Exercise 56: Assignment with a Returned Value

Call the processArg function with an argument of 7 and assign its return value to the variable processed.
```
// Setup
let processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line
processed = processArg(7)
```


### Exercise 57: Stand in Line

Write a function nextInLine which takes an array (arr) and a number (item) as arguments.
Add the number to the end of the array, then remove the first element of the array.
The nextInLine function should then return the element that was removed.

```
function nextInLine(arr, item) {
  // Only change code below this line
  arr.push(item);
  return arr.shift();
  // Only change code above this line
}
```


### Exercise 58: Understanding Boolean Values

Modify the welcomeToBooleans function so that it returns true instead of false when the run button is clicked.
```
function welcomeToBooleans() {
  // Only change code below this line

  return true; // Change this line

  // Only change code above this line
}
```


### Exercise 59: Use Conditional Logic with If Statements

Create an if statement inside the function to return Yes, that was true if the parameter wasThatTrue is true and return No, that was false otherwise.

```
function trueOrFalse(wasThatTrue) {
  // Only change code below this line

  if(wasThatTrue) {
    return "Yes, that was true";
  }
  return "No, that was false"
  // Only change code above this line

}
```


### Exercise 60: Comparison with the Equality Operator

Add the equality operator to the indicated line so that the function will return the string Equal when val is equivalent to 12.
```
// Setup
function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testEqual(10);
```
### Exercise 61: Comparison with the Strict Equality Operator

Use the strict equality operator in the if statement so the function will return the string Equal when val is strictly equal to 7.
```
// Setup
function testStrict(val) {
  if (val===7) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testStrict(10);
```

### Exercise 62: Practice comparing different values

The compareEquality function in the editor compares two values using the equality operator. Modify the function so that it returns the string Equal only when the values are strictly equal.
```
// Setup
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

compareEquality(10, "10");
```

### Exercise 63: Comparison with the Inequality Operator
Add the inequality operator != in the if statement so that the function will return the string Not Equal when val is not equivalent to 99.
```
// Setup
function testNotEqual(val) {
  if (val != 99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

testNotEqual(10); 
```


### Exercise 64: Comparison with the Strict Inequality Operator
Add the strict inequality operator to the if statement so the function will return the string Not Equal when val is not strictly equal to 17
```
// Setup
function testStrictNotEqual(val) {
  if (val !== 17) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

testStrictNotEqual(10);
```

### Exercise 65: Comparison with the Greater Than Operator
Add the greater than operator to the indicated lines so that the return statements make sense.
```
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }

  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

testGreaterThan(10);
```

### Exercise 66: Comparison with the Greater Than Or Equal to Operator
Add the greater than or equal to operator to the indicated lines so that the return statements make sense.
```
function testGreaterOrEqual(val) {
  if (val >= 20) {  // Change this line
    return "20 or Over";
  }

  if (val >=10) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

testGreaterOrEqual(10);
```


### Exercise 67: Comparison with the Less Than Operator
Add the less than operator to the indicated lines so that the return statements make sense. 
```
function testLessThan(val) {
  if (val < 25) {  // Change this line
    return "Under 25";
  }

  if (val < 55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

testLessThan(10);
```

### Exercise 68: Comparison with the Less Than or Equal to Operator
Add the less than or equal to operator to the indicated lines so that the return statements make sense.

```
function testLessOrEqual(val) {
  if (val <= 12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }

  if (val <= 24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

testLessOrEqual(10);
```
### Exercise 69: Comparisons with the Logical AND Operator
Replace the two if statements with one statement, using the && operator, which will return the string Yes if val is less than or equal to 50 and greater than or equal to 25. Otherwise, will return the string No.
```
function testLogicalAnd(val) {
  // Only change code below this line

  if (val <= 50 && val >= 25) {
         return "Yes";
    }
    // Only change code above this line
  return "No";
}

testLogicalAnd(10);
```

### Exercise 70: Comparisons with the Logical OR Operator
Combine the two if statements into one statement which returns the string Outside if val is not between 10 and 20, inclusive. Otherwise, return the string Inside.
```
function testLogicalOr(val) {
  // Only change code below this line

  if (val < 10 || val > 20) {
    return "Outside";
  }

  // Only change code above this line
  return "Inside";
}

testLogicalOr(15);
```


### Exercise 71: Introducing Else Statements

Combine the if statements into a single if/else statement. 
```
function testElse(val) {
  let result = "";
  // Only change code below this line

  if (val > 5) {
    result = "Bigger than 5";
  }

    else {
      result = "5 or Smaller";
  }

  // Only change code above this line
  return result;
}

testElse(4);
```


### Exercise 72: Introducing Else If Statements

Convert the logic to use `else if` statements. 
```
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }

  else if (val < 5) {
    return "Smaller than 5";
  }

  else { return "Between 5 and 10";
  }
}

testElseIf(7);
```

### Exercise 73: Logical Order in If Else Statements

Change the order of logic in the function so that it will return the correct statements in all cases.

```
function orderMyLogic(val) {
  if (val < 5) {
    return "Less than 5";
  } else if (val < 10) {
    return "Less than 10";
  } else {
    return "Greater than or equal to 10";
  }
}



orderMyLogic(7);
```

### Exercise 74: Chaining If Else Statements

Write chained if/else if statements to fulfill the following conditions:

num < 5 - return Tiny
num < 10 - return Small
num < 15 - return Medium
num < 20 - return Large
num >= 20 - return Huge

```
function testSize(num) {
  // Only change code below this line
if (num < 5) {
  return "Tiny"; 
} else if (num < 10){
  return "Small";
} else if (num < 15){
  return "Medium";
} else if (num < 20){
  return "Large";
} else {
  return "Huge";
}
  // Only change code above this line
}

testSize(7);
```

### Exercise 75: Golf Code
In the game of Golf, each hole has a par, meaning, the average number of strokes a golfer is expected to make in order to sink the ball in the hole to complete the play. Depending on how far above or below par your strokes are, there is a different nickname.

Your function will be passed par and strokes arguments. Return the correct string according to this table which lists the strokes in order of priority; top (highest) to bottom (lowest):

| Strokes | Return |
| --- | --- |
| 1	| "Hole-in-one!" |
| <= par - 2 |	"Eagle" |
| par - 1 |"Birdie" |
| par | "Par"|
| par + 1 | "Bogey" |
| par + 2 | "Double Bogey" |
| >= par + 3 | "Go Home!" |

par and strokes will always be numeric and positive. We have added an array of all the names for your convenience.


```
const names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];

function golfScore(par, strokes) {
  // Only change code below this line
  if (strokes == 1){
    return names[0];
  }
  else if (strokes <= par - 2){
    return names[1];
  }
  else if (strokes == par - 1){
    return names[2];
  }
  else if (strokes == par){
    return names[3];
  }
  else if (strokes == par + 1){
    return names[4];
  }
  else if (strokes == par + 2)
    return names[5];
  else{
    return names[6];
  }
  // Only change code above this line
}

golfScore(5, 4);
```


### Exercise 76: Selecting from Many Options with Switch Statements

Write a switch statement which tests val and sets answer for the following conditions:
1 - alpha
2 - beta
3 - gamma
4 - delta

```
function caseInSwitch(val) {
  let answer = "";
  // Only change code below this line
switch (val) {
  case 1:
    answer = "alpha";
    break;
  case 2:
    answer = "beta";
    break;
  case 3: 
    answer = "gamma";
    break;
  case 4:
    answer = "delta";
    break;
}

  // Only change code above this line
  return answer;
}

caseInSwitch(1);
```


### Exercise 77: Adding a Default Option in Switch Statements

Write a switch statement to set answer for the following conditions:
a - apple
b - bird
c - cat
default - stuff

```
function switchOfStuff(val) {
  let answer = "";
  // Only change code below this line

switch (val) {
  case "a":
    answer = "apple";
    break;
  case "b":
    answer = "bird";
    break;
  case "c": 
    answer = "cat";
    break;
  
  default:
    answer = "stuff";
    break;
}
  // Only change code above this line
  return answer;
}

switchOfStuff(1);
```

### Exercise 78: Multiple Identical Option in Switch Statements

Write a switch statement to set answer for the following ranges:
1-3 - Low
4-6 - Mid
7-9 - High

```
function sequentialSizes(val) {
  let answer = "";
  // Only change code below this line
switch (val) {
  case 1:
  case 2:
  case 3: 
    answer = "Low";
    break;
  case 4:
  case 5:
  case 6:
    answer = "Mid";
    break;
  case 7:
  case 8:
  case 9:
    answer = "High";
}

  // Only change code above this line
  return answer;
}

sequentialSizes(1);
```


### Exercise 79: Replacing If Else Chains with Switch

Change the chained if/else if statements into a switch statement.

```
function chainToSwitch(val) {
  let answer = "";
  // Only change code below this line

switch (val){
  case "bob":
    answer = "Marley";
    break;
  case 42:
    answer = "The Answer";
    break;
  case 1: 
    answer = "There is no #1";
    break;
  case 99:
    answer = "Missed me by this much!";
    break;
  case 7:
    answer = "Ate Nine";
    break;
  }


  // Only change code above this line
  return answer;
}

chainToSwitch(7);
```

### Exercise 80: Returning Boolean Values From Functions

Fix the function isLess to remove the if/else statements.

```
function isLess(a, b) {
  // Only change code below this line
     return a < b;
  // Only change code above this line
}

isLess(10, 15);
```


### Exercise 81: Return Early Pattern for Functions
Modify the function abTest so that if a or b are less than 0 the function will immediately exit with a value of undefined.
```
// Setup
function abTest(a, b) {
  // Only change code below this line

if ( a < 0 || b < 0 ) {
    return undefined;
}


  // Only change code above this line

  return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
}

abTest(2,2);
```


### Exercise 82: Counting Cards

In the casino game Blackjack, a player can determine whether they have an advantage on the next hand over the house by keeping track of the relative number of high and low cards remaining in the deck. This is called Card Counting.

Having more high cards remaining in the deck favors the player. Each card is assigned a value according to the table below. When the count is positive, the player should bet high. When the count is zero or negative, the player should bet low.

Count Change	Cards
+1	2, 3, 4, 5, 6
0	7, 8, 9
-1	10, 'J', 'Q', 'K', 'A'
You will write a card counting function. It will receive a card parameter, which can be a number or a string, and increment or decrement the global count variable according to the card's value (see table). The function will then return a string with the current count and the string Bet if the count is positive, or Hold if the count is zero or negative. The current count and the player's decision (Bet or Hold) should be separated by a single space.

Example Outputs: -3 Hold or 5 Bet

Hint
Do NOT reset count to 0 when value is 7, 8, or 9.
Do NOT return an array.
Do NOT include quotes (single or double) in the output.

```
let count = 0;

function cc(card) {
  // Only change code below this line
  switch (card) {
    case 2:
    case 3:
    case 4:
    case 5:
    case 6:
      count++;
      break;
    case 10:
    case "J":
    case "Q":
    case "K":
    case "A":
      count--;
      break;
  }
  if (count > 0) {
    return count + " Bet";
  } else {
    return count + " Hold";
  }
  // Only change code above this line
}

cc(2); cc(3); cc(7); cc('K'); cc('A');
```



### Exercise 83: Build JavaScript Objects

Make an object that represents a dog called myDog which contains the properties name (a string), legs, tails and friends.

You can set these object properties to whatever values you want, as long as name is a string, legs and tails are numbers, and friends is an array.

```
const myDog = {
  // Only change code below this line
  "name": "doggy",
  "legs": 4,
  "tails": 1,
  "friends": ["me", "bro", "sis"]

  // Only change code above this line
};
```



### Exercise 84: Accessing Object Properties with Dot Notation

Read in the property values of testObj using dot notation. Set the variable hatValue equal to the object's property hat and set the variable shirtValue equal to the object's property shirt.

```
// Setup
const testObj = {
  "hat": "ballcap",
  "shirt": "jersey",
  "shoes": "cleats"
};

// Only change code below this line
const hatValue = testObj.hat;      // Change this line
const shirtValue = testObj.shirt;    // Change this line
```



### Exercise 85: Accessing Object Properties with Bracket Notation


Read the values of the properties an entree and the drink of testObj using bracket notation and assign them to entreeValue and drinkValue respectively.

```
// Setup
const testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};

// Only change code below this line
const entreeValue = testObj["an entree"];   // Change this line
const drinkValue = testObj["the drink"];    // Change this line
```



### Exercise 86: Accessing Object Properties with Variables


Set the playerNumber variable to 16. Then, use the variable to look up the player's name and assign it to player.

```
// Setup
const testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};

// Only change code below this line
const playerNumber = 16;  // Change this line
const player = testObj[playerNumber];   // Change this line
```



### Exercise 87: Updating Object Properties

Update the myDog object's name property. Let's change her name from Coder to Happy Coder. You can use either dot or bracket notation.

```
// Setup
const myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line

myDog.name = "Happy Coder"
```



### Exercise 88: Add New Properties to a JavaScript Object

Add a bark property to myDog and set it to a dog sound, such as "woof". You may use either dot or bracket notation.

```
const myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

myDog.bark = "woof";
```


### Exercise 89: Delete Properties from a JavaScript Object

Delete the tails property from myDog. You may use either dot or bracket notation.

```
// Setup
const myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};

// Only change code below this line
delete myDog.tails;
```


### Exercise 90: Using Objects for Lookups

Convert the switch statement into an object called lookup. Use it to look up val and assign the associated string to the result variable.

```
// Setup
function phoneticLookup(val) {
  let result = "";

  // Only change code below this line
var lookup = {
    "alpha": "Adams",
    "bravo": "Boston",
    "charlie": "Chicago",
    "delta": "Denver",
    "echo": "Easy",
    "foxtrot": "Frank"
  };
  result = lookup[val];
  // Only change code above this line
  return result;
}

phoneticLookup("charlie");
```



### Exercise 91: Testing Objects for Properties

Modify the function checkObj to test if an object passed to the function (obj) contains a specific property (checkProp). If the property is found, return that property's value. If not, return "Not Found".

```
function checkObj(obj, checkProp) {
  // Only change code below this line
if (obj.hasOwnProperty(checkProp)) {
    return obj[checkProp];
  } else {
    return "Not Found";
  }
  // Only change code above this line
}
```



### Exercise 92: Manipulating Complex Objects

Add a new album to the myMusic array. Add artist and title strings, release_year number, and a formats array of strings.

```
const myMusic = [
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  },
  {
    "artist": "Diana Krall",
    "title": "So Nice",
    "release_year": 2007,
    "formats": [
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  }
];
```



### Exercise 93: Accessing Nested Objects

Access the myStorage object and assign the contents of the glove box property to the gloveBoxContents variable. Use dot notation for all properties where possible, otherwise use bracket notation.

```
const myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};

const gloveBoxContents = myStorage.car.inside["glove box"];
```



### Exercise 94: Accessing Nested Arrays

Using dot and bracket notation, set the variable secondTree to the second item in the trees list from the myPlants object.

```
const myPlants = [
  {
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }
];

const secondTree = myPlants[1].list[1];
```

### Exercise 95: Record Collection

You are given an object literal representing a part of your musical album collection. Each album has a unique id number as its key and several other properties. Not all albums have complete information.

You start with an `updateRecords` function that takes an object literal, records, containing the musical album collection, an `id`, a `prop` (like `artist` or `tracks`), and a `value`. Complete the function using the rules below to modify the object passed to the function.

Your function must always return the entire record collection object.
- If prop **isn't** tracks **and** value **isn't** an empty string, update or set that album's prop to value.
- If prop **is** tracks **but** the album **doesn't** have a tracks property, create an empty array and add value to it.
- If prop is tracks and value isn't an empty string, add value to the end of the album's existing tracks array.
- If value is an empty string, delete the given prop property from the album.

Note: A copy of the recordCollection object is used for the tests.

```
// Setup
const recordCollection = {
  2548: {
    albumTitle: 'Slippery When Wet',
    artist: 'Bon Jovi',
    tracks: ['Let It Rock', 'You Give Love a Bad Name']
  },
  2468: {
    albumTitle: '1999',
    artist: 'Prince',
    tracks: ['1999', 'Little Red Corvette'] //tracks contains album title
  },
  1245: {
    artist: 'Robert Palmer',
    tracks: [] //empty
  },
  5439: {
    albumTitle: 'ABBA Gold' //no further detal
  }
};

// Only change code below this line
function updateRecords(records, id, prop, value) {
  if (prop !== "tracks" && value !== "") {
    records[id][prop] = value;
  } else if (prop === "tracks" && value !== "" && records[id].hasOwnProperty("tracks") === false) {
    records[id][prop] = [value];
  } else if (prop === "tracks" && value !== "") {
    records[id][prop].push(value);
  } else if (value === "") {
    delete records[id][prop];
  }
  return records;
}

updateRecords(recordCollection, 5439, 'artist', 'ABBA');
```


### Exercise 96: Iterate with JavaScript While Loops

Add the numbers 5 through 0 (inclusive) in descending order to `myArray` using a `while` loop.

```
// Setup
const myArray = [];

// Only change code below this line
let i = 5;

while (i >= 0) {
  myArray.push(i);
  i--;
}
```

### Exercise 97: Iterate with JavaScript For Loops

Use `for` loop to push the values 1 through 5 onto `myArray`

```
// Setup
const myArray = [];

// Only change code below this line

for (let i=1; i <=5; i++) {
  myArray.push(i);
}
```


### Exercise 98: Iterate Odd Numbers With a For Loop

Push the odd numbers from 1 through 9 to myArray using a `for` loop.

```
// Setup
const myArray = [];

// Only change code below this line

for (let i = 1; i <=9; i +=2){
  myArray.push(i);
}
```



### Exercise 99: Count Backwards With a For Loop

Push the odd numbers from 9 through 1 to `myArray` using `for` loop. 

```
// Setup
const myArray = [];

// Only change code below this line
for (let i = 9; i >= 1; i-=2 ){
  myArray.push(i);
}
```



### Exercise 100: Iterate Through an Array with a For Loop

Declare and initialize a variable total to 0. Use a for loop to add the value of each element of the myArr array to total.

```
// Setup
const myArr = [2, 3, 4, 5, 6];

// Only change code below this line

let total = 0

for (let i = 0; i < myArr.length; i++){
  total += myArr[i];
}
```



### Exercise 101: Nesting For Loops

Modify function multiplyAll so that it returns the product of all the numbers in the sub-arrays of arr.

```
function multiplyAll(arr) {
  let product = 1;
  // Only change code below this line
for (let i = 0; i < arr.length;i++) {
  for (let j = 0;j<arr[i].length;j++){
    product *=arr[i][j];
  }
}
  // Only change code above this line
  return product;
}

multiplyAll([[1, 2], [3, 4], [5, 6, 7]]);
```



### Exercise 102: Iterate with JavaScript Do... While Loops


Change the while loop in the code to a do...while loop so the loop will push only the number 10 to myArray, and i will be equal to 11 when your code has finished running.

```
// Setup
const myArray = [];
let i = 10;

// Only change code below this line
do {
  myArray.push(i);
  i++;
} while (i < 11)
```



### Exercise 103: Replace Loops using Recursion


Write a recursive function, sum(arr, n), that returns the sum of the first n elements of an array arr.


```
function sum(arr, n) {
  // Only change code below this line
  if (n <= 0) {
    return 0;
  } else {
    return sum(arr, n-1) + arr[n -1];
  }
  // Only change code above this line
}
```



### Exercise 104: Profile Lookup

We have an array of objects representing different people in our contacts lists.

A lookUpProfile function that takes name and a property (prop) as arguments has been pre-written for you.

The function should check if name is an actual contact's firstName and the given property (prop) is a property of that contact.

If both are true, then return the "value" of that property.

If name does not correspond to any contacts then return the string No such contact.

If prop does not correspond to any valid properties of a contact found to match name then return the string No such property.

```
// Setup
const contacts = [
  {
    firstName: "Akira",
    lastName: "Laine",
    number: "0543236543",
    likes: ["Pizza", "Coding", "Brownie Points"],
  },
  {
    firstName: "Harry",
    lastName: "Potter",
    number: "0994372684",
    likes: ["Hogwarts", "Magic", "Hagrid"],
  },
  {
    firstName: "Sherlock",
    lastName: "Holmes",
    number: "0487345643",
    likes: ["Intriguing Cases", "Violin"],
  },
  {
    firstName: "Kristian",
    lastName: "Vos",
    number: "unknown",
    likes: ["JavaScript", "Gaming", "Foxes"],
  },
];

function lookUpProfile(name, prop) {
  // Only change code below this line
    for (var i = 0; i < contacts.length; i++) {
    if(contacts[i].firstName === name) {
      return contacts[i][prop] || "No such property"
    }
  }
  return "No such contact";
  // Only change code above this line
}

lookUpProfile("Akira", "likes");
```


### Exercise 105: Generate Random Fractions with JavaScript

Change randomFraction to return a random number instead of returning 0.

```
function randomFraction() {

  // Only change code below this line

  return Math.random();

  // Only change code above this line
}
```



### Exercise 106: Generate Random Whole Numbers with JavaScript


Use this technique to generate and return a random whole number between 0 and 9.

```
function randomWholeNum() {

  // Only change code below this line

  return Math.floor(Math.random()*10);
}
```



### Exercise 107: Generate Random Whole Numbers within a Range


Create a function called randomRange that takes a range myMin and myMax and returns a random whole number that's greater than or equal to myMin, and is less than or equal to myMax, inclusive.

```
function randomRange(myMin, myMax) {
  // Only change code below this line
  return Math.floor(Math.random()* (myMax - myMin +1)) + myMin;
  // Only change code above this line
}
```


### Exercise 108: Use the parsenInt Function

Use parseInt() in the convertToInteger function so it converts the input string str into an integer, and returns it.

```
function convertToInteger(str) {
  return parseInt(str);
}

convertToInteger("56");
```



### Exercise 109: Use the parseInt Function with a Radix

Use parseInt() in the convertToInteger function so it converts a binary number to an integer and returns it. 

```
function convertToInteger(str) {
  return parseInt(str, 2)
}

convertToInteger("10011");
```



### Exercise 110: Use the Conditional (Ternary) Operator

Use the conditional operator in the checkEqual function to check if two numbers are equal or not. The function should return either the string Equal or the string Not Equal.

```
function checkEqual(a, b) {
  return a == b ? "Equal" : "Not Equal";
}

checkEqual(1, 2);
```



