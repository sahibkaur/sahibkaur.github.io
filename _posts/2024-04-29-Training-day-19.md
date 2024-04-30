---
layout: post
title: "Training day 19 - JavaScript Basic to Beginners [Functions]"
author: "Sahibee"
---

Heloo people!!

These are the notes of what I learned:

Functions

With var keyword, the scope of the variable is not limited to the code block but rather to the function it is defined in.
That’s why it is better to use the let keyword

Rest operator (…) is used to write down the rest of the arguments.

This keyword
this references the object hat is executing the current function

If this keyword is in a method (that is part of an object), then the “this” keyword refers to the object.
Otherwise, if it is in a regular function, it points to the window object (global object).

Const video = { title: ‘a’,
Tags: [‘a’, ‘b’, ‘c’],
showTags() {
Const self = this;
This.tags.forEach(function(tag) {
console.log(self.title, tag);
console.log(this); //this refers to global object here
});
}}

^^ Not a preferred approach

Const video = { title: ‘a’,
Tags: [‘a’, ‘b’, ‘c’],
showTags() {
This.tags.forEach(function(tag) {
console.log(self.title, tag);
}.bind(this));
}}
^^ A better solution, but there’s another newer approach

Const video = { title: ‘a’,
Tags: [‘a’, ‘b’, ‘c’],
showTags() {
This.tags.forEach((tag) => console.log(self.title, tag));
}}
^^ Arrow functions inherit the this property

Array.isArray([]); //returns true
Array.isArray({}); //returns false

Object Oriented Programming with JavaScript

- The best functions are those with no parameters. - Robert C Martin

Next, I'll work on Objects and Prototypes in this OOPs course. I will try my best to complete this entire course but I have to visit the doctor, so can't confirm it.

Till then,
Toodles!
