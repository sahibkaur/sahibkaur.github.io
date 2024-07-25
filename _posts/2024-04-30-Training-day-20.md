---
layout: post
title: "Training day 20 - Object Oriented Programming with JavaScript"
author: "Sahibee"
---

Stop using var
Use Const or let

```
//Constructor function
function Circle(radius) {
console.log(‘this’, this);
This.radius = radius;
this.draw = function() {
Console.log(‘draw’);
}
}

const another = new Circle(1); //this will log the new object

const second = Circle(1); //this will log the (global) window object
Object.defineProprty(this, ‘defaultLocation’, {
get: function() {
return defaultLocation;
},
set: function(value) {
if(!value.x || !value.y)
throw new Error(‘Invalid Location.’);
defaultLocation = value;
 }

});
```
