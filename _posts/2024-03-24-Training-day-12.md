---
layout: post
title: "Training day 12 - JavaScript Basic to Beginners"
author: "Sahibee"
---

Heloo people!!

Following notes:

- Installed the Live Server extension on VS code which helps to run the code directly onto the browser.

- Usually we run the JavaScript on Browsers but the introduction of Node made it possible to run it outside of the browser.

//Comments are wriiten like this in JavaScript

- Console.log("Hello World")
  "Hello World" is a string here.

- Separation of Concerns
  Separate HTML (Structure), CSS (styling), JavaScript (Behaviour) in different files.

- Downloaded Node from node.org.
- Then opened the terminal, opened the project folder and used the following command.node index.jsIt printed “Hello World”.This was my code in index.jsconsole.log(“Hello World”);We did the above to test node and how we can run the Javascript without using browser using Node. But we won’t be learning node in this course.
- Variable names rules
  //Cannot be a reserved keyword
  //variable names should be meaningful
  //Cannot start with a number
  //Cannot contain space or hyphen(-)

- Value of a constant doesn’t change. We use the keyword const to define a constant.

- Primitive Data TypesStringNumberBooleanUndefined null
- Reference Data TypeObjectsArraysFunctions

Object syntaxlet person = {
name: ‘abc’,
age: 20
};

Dot Notation to access or change a property:
person.name = ‘John’;
console.log(person.name);

Bracket Notation
person[‘name’]=‘Mary’;

Dynamicallylet selection = ‘name’;
person[selection] = ‘Mary’;

Arrays
let selectedColors = [‘red’, ‘blue’];

Functions
function greet(name) {
console.log(‘Hello ’ + name);
}
greet(‘Sahib’);

‘Sahib’ is an argument and name is a parameter.

Two Types of Functions:- User Defined

- Built-in

Then I learned about Operators.

Strict Equality (Type + Value)
Console.log(1 === 1) //true
console.log(‘1’ === 1)//false

Lose Equality (Value)
console.log(1 == 1) //true
console.log(‘1’ == 1) //true

- Ternary Operator
- Logical Operators

false || true
answer is true
If we have false || ‘Sahib’
answer is ‘Sahib’

// Falsy (false)
// undefined
// null
// 0
// false
// ‘’
// NaN

// Anything that is not False is Truth

false || 1 || 2
When the operand is found that is truth, it is returned - no matter how many Truthy values are on the right.
It is called shortcutting.

This can be used in a case like this:let userColor = undefined;
let defaultColor = ‘blue’;
let currentColor = userColor || defaultColor;

console.log(currentColor);
//prints blue

I will continue the rest on Tuesday.

Byeee!
