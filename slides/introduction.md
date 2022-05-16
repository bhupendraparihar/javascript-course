---
marp: true
---

# Who am I?
+ Bhupendra Singh Parihar
+ 12+ years of experience in devloping Web Applications
+ JavaScript Enthusiast

---
# Who introduced JavaScript?
Brendan Eich created JavaScript in 1995 while he was at Netscape Communications Corporation, the creators of the legendary Netscape Navigator web browser. At the time, the Java coding language was rapidly gaining traction and Netscape Communications was working to make it available in Netscape Communicator.

However, Java was too large and too complex to appeal to amateurs, scripters, and designers. In order to solve this problem, Netscape Communications contracted Brendan Eich to design a versatile programming language that could speed up web development and serve as a scripting companion for Java. 

---
# Why was JavaScript created?
Back in 1995, Netscape Communicator (a paid internet browser) was by far the most popular web browser in the world. The founder of Netscape Communications, Marc Andreeseen, wanted to make the web more dynamic by making animations, user interaction, and other types of automation a standard part of any website. 

He also knew that Microsoft was hard at work on their own browser, Internet Explorer, and wanted to make Netscape Communicator more attractive to developers by equipping it with both an enterprise-level coding language (Java) and a smaller scripting language (JavaScript).

---
# Where can you run JavaScript
+ Browsers
+ Nodejs (Backend framework for JavaScript)
+ JavaScript playgrounds(jsbin, jsfiddle, codepen etc)

---
# Hello World

```javascript
console.log('Hello World');
```

[Run it here](https://jsbin.com/katutip/edit?html,js,console,output)

---
# Pythagorous Theorem

$$ perpendicular^{2} + base^{2} = hypotenuse^{2} $$ 

Find the value of hypotenuse, if pependicular is 8cm and base is 6cm.

Tell me what is the answer?

---
# Lets write some code

```javascript
var p = 8;
var b = 6;

var h = Math.sqrt(p*p + b*b);

console.log(h);
```

---
# Declaring variables
Variables are a way to give name to a value, so we can reuse that value by calling its name, just like we give names to buildings to refer them in conversation.
```javascript
var p = 8;
var b = 6;
var name = "John";
```
Remember we use = operator to assign value to a variable

Write a program to declare a variable name = 'your_name' and use console.log function to print 'Hello your_name'

---
# Different types of value
 In JavaScript, a variable can hold different types of values

 ## Primitive types
 + String
 + Number
 + Boolean
 + undefined
 + null
 + Symbol
 + BigInt

---

# Write a program

Write a program to declare two variables name and age
and print the statement 'Rahul is 22 years old'

---

# Case Sensitivity in Variables
In JavaScript all variables and function names are case sensitive. This means that capitalization matters.

MYVAR is not the same as MyVar nor myvar. It is possible to have multiple distinct variables with the same name but different casing. It is strongly recommended that for the sake of clarity, you do not use this language feature.

---

Write variable names in JavaScript in camelCase. In camelCase, multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized.

Examples:
```javascript
var someVariable;
var anotherVariableName;
var thisVariableNameIsSoLong;
```

---
# Write a program
Create a program to calculate area of circle

Area of Circle is 
$$  Area of Cicle = pi * r^{2}$$

use pi = 3.14

[Lets try this code](https://jsbin.com/xavoset/edit?html,js,output)

---

# Write a program

Create a program to find Area of triangle

$$ Area of triangle = 1/2 * base * height $$

---

# Arithmatic operators

| Operator | Description |
| ------- | ---------- |
| +	| Addition |
| -	| Subtraction |
| * | Multiplication |
| ** | Exponentiation |
| /	| Division |
| %	| Modulus (Remainder) |
| ++ | Increment |
| -- | Decrement |

---
# Concatenating Strings with Plus Operator
In JavaScript, when the + operator is used with a String value, it is called the concatenation operator. You can build a new string out of other strings by concatenating them together.

Example
```javascript
'My name is Alan,' + ' I concatenate.'
```
Note: Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.

Example:
```javascript
const ourStr = "I come first. " + "I come second.";
```
The string I come first. I come second. would be displayed in the console.

---

# Write a program

Write a program to print your full name(firstname + middlename + lastname) in the console.

---
# Find the Length of a String

You can find the length of a String value by writing .length after the string variable or string literal.

```javascript
console.log("Alan Peter".length);
```

The value 10 would be displayed in the console. Note that the space character between "Alan" and "Peter" is also counted.

For example, if we created a variable const firstName = "Ada", we could find out how long the string Ada is by using the firstName.length property.

---

# Use Bracket Notation with String

Bracket notation is a way to get a character at a specific index within a string.

Most modern programming languages, like JavaScript, don't start counting at 1 like humans do. They start at 0. This is referred to as Zero-based indexing.

For example, the character at index 0 in the word Charles is C. So if const firstName = "Charles", you can get the value of the first letter of the string by using firstName[0].

Example:
```javascript
const firstName = "Charles";
const firstLetter = firstName[0];
```
firstLetter would have a value of the string C.

---

# Understand String Immutability
In JavaScript, String values are immutable, which means that they cannot be altered once created.

For example, the following code:
```javascript
let myStr = "Bob";
myStr[0] = "J";
```
cannot change the value of myStr to Job, because the contents of myStr cannot be altered. Note that this does not mean that myStr cannot be changed, just that the individual characters of a string literal cannot be changed. The only way to change myStr would be to assign it with a new string, like this:
```javascript
let myStr = "Bob";
myStr = "Job";
```
