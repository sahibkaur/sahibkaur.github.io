---
layout: post
title: "Training day 18 - JavaScript Basic to Beginners [Arrays]"
author: "Sahibee"
---

Heloo people!!

These are the notes of what I learned:

Objects

- If a function is part of an object, in object oriented programming terms - it is called a method.

Factory function

- These factory functions produce objects.

Function createCircle() {
Const circle = {
Radius: 1,

    }

}

numbers.shift() - add numbers to start of the array
numbers.splice() - add numbers at particular position
numbers.indexOf() - returns the index of element in the array

- If the element isn’t in the array, it returns -1
  numbers.includes() - checks if element is present in the array
  ]

numbers.find() - it takes a function as a parameter, which can help define, what to find in the array.

numbers.pop() - remove the last element from the array and. returns it
numbers.shift() - removes element from the beginning and returns it

Emptying an array:
Numbers = []
numbers.length(0, numbers.length)

- Not recommended
- while(numbers.lengh>0)
  Numbers.pop()

concat() - combine two arrays
slice() - slice two arrays

Spread operator
Const combines = […first, …second];

Array to string
Const joined = numbers.join(‘,’);

String to array
Const parts = message.split(‘ ‘);

numbers.every() - checks to see if every element in the array matches the criteria given
numbers.some() - check if at least one element in the array matches the given criteria

//Function Declaration
walk();

Function walk() {
console.log(‘walk’);
}

//Function Expression

run() //can’t do that

Const run = function() {
console.log(‘run’);
}
