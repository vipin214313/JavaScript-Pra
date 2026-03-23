# JavaScript-Pra
 What is JavaScript?
JavaScript is a programming language used for creating dynamic content on websites.
It is a lightweight, cross-platform, and single-threaded programming language.

“JavaScript is an interpreted language that runs code line by line, making it flexible and easy to learn. It’s mainly used to build dynamic and interactive features in websites.”

🧠 History:
    • Created by Brendan Eich in 1995
    • He was an engineer at Netscape
    • Originally called LiveScript, but later renamed to JavaScript

There are 3 main methods:
    1. Inline JavaScript
    2. Internal JavaScript (<script> tag)
        ○ Inside <head> section
        ○ Inside <body> section
    
    3. External JavaScript (Using .js file)
✅ JavaScript Variables
"A JavaScript variable is a container that stores data values. It acts as a symbolic name for a memory location. Variables are used to hold data that can be accessed or manipulated in the program."


Rules of Naming Variables in JavaScript :-
There are some rules while declaring a JavaScript variable (also known as identifiers).
    • Name must start with a letter (a to z or A to Z), underscore( _ ), or dollar( $ ) sign.
    • After the first letter, we can use digits (0 to 9), for example, value1.
    • JavaScript variables are case-sensitive; for example, x and X are different variables.

🟨 1. JavaScript Local Variable
A local variable is declared inside a function or block {} and it is accessible only within that function or block only.
🟩 2. JavaScript Global Variable
A global variable Declared outside any function  or Block  and it  is accessible everywhere in your program: inside functions, outside functions, and in all blocks.

👉 In browsers, global variables become properties of the window object.
👉 In Node.js, they are attached to the global object.

Data types:-
    • JavaScript is a dynamic type language → You don’t need to declare the type of variable (JS decides automatically).

Data Type	Description	Example
Number	Stores integers, floating points, and special values (Infinity, -Infinity, NaN).	let n1 = 2; let n2 = 1.5; let n3 = Infinity; let n4 = 'abc'/2; // NaN
String	Sequence of characters, written in "double", 'single', or backticks (template literals).	"Hello", 'World', `Hi ${name}`
Boolean	Logical values → true or false.	let isCoding = true;
Null	Special type with single value null → means nothing / empty / unknown.	let age = null;
Undefined	Variable declared but not assigned → undefined.	let x; console.log(x); // undefined
Symbol (ES6)	Unique & immutable identifier, often used as object property keys.	let s1 = Symbol("id"); let s2 = Symbol("id"); // s1 !== s2
BigInt (ES11)	For very large integers beyond 2^53 - 1.	let big = 123456789012345678901234567890n;

Non-Primitive (Reference) Data Types:
Non-primitive data types, also known as reference types, are objects and derived data types. They can store collections of values or more complex entities.

4. Types of Variables in JavaScript
In modern JavaScript, we mainly have three types of variable declarations:
Type	Scope / Usage	Can be Reassigned?	Example
var	Function-scoped, can be redeclared	Yes	var age = 25;
let	Block-scoped, cannot be redeclared	Yes	let score = 50;
const	Block-scoped, cannot be redeclared	No (constant)	const pi = 3.14;

1️⃣ What is Type Conversion?
In JavaScript Type Conversion can be defined as converting the data type of the variables from one type to the other manually by the programmer(explicitly) or automatically by the JavaScript(implicitly).

Two kinds of conversion:
• Implicit Type Conversion (Coercion): Implicit Type Conversion occurs automatically by the JavaScript.
Explicit Type Conversion: Explicit Type Conversion occurs when the programmer manually changes the type of the variables using the function Number(), String(), and Boolean().

JavaScript Operators – Complete Notes
Definition:
JavaScript operators are symbols or keywords that perform operations on operands (values, variables, or expressions). Operators can be classified into:
    1. Arithmetic
    2. Assignment
    3. Comparison
    4. Logical
    5. Bitwise
    6. Ternary
    7. Comma
    8. Unary
    9. Relational
    10. BigInt
    11.String
