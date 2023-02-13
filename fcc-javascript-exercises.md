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

### Exercise 66: Practice comparing different values
### Exercise 67: Practice comparing different values
### Exercise 68: Practice comparing different values
### Exercise 69: Practice comparing different values
### Exercise 70: Practice comparing different values















