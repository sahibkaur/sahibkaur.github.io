---
layout: post
title: "Training day 15 - JavaScript Basic to Beginners"
author: "Sahibee"
---

Heloo people!!

Following notes:

Objects

- If ax function is part of an object, in object oriented programming terms - it is called a method.

Factory function

- These factory functions produce objects.

function createCircle(radius) {
return {
radius: radius,
draw: function() {
console.log('draw');
}
}
}

if key and value are same, we can directly use value - like this:

function createCircle(radius) {
return {
radius,
draw: function() {
console.log('draw');
}
}
}

We can even simplify the draw method

```function createCircle(radius) {
        return {
            radius,
            draw() {
                    console.log('draw');
            }
        }
    }
```

- Camel Notation: oneTwoThreeFour
- Pascal Notation: OneTwoThreeFour

- Constructor Function

```
function Circle(radius) {
    this.radius = radius,
    this.draw = function() {
        console.log('draw');
    }
}

const circle = new Circle(1);
```

- Remove property from object

```
const circle = {
    radius: 1
};

circle.color = "yellow";
delete circle.color;
```

Here we see, it seems like we modified the object but we can add or remove properties but cannot reassign the object.

- Every object has a constructor property which references the constructor that was used to create the object.
  JavaScript has some built-in constructors:
- Object()
- new String(); // Can be called using '', "", ``
- new Boolean(); //true, false
- new Number(); //1, 2, 3

- In JavaScript, functions are Objects. This is confusing, I'll read more about it.

Byeee!
