---
layout: post
title: "Training day 16 - JavaScript Basic to Beginners"
author: "Sahibee"
---

Heloo people!!

- Value Types: Number, String, Boolean, Symbol, Undefined, Null
  Reference Types: Objects, Functions, Arrays

- Functions are Objects. Arrays are also Objects. Therefore Reference types have only Objects technically.

- Primitives are copied by value. Objects are copied by their reference.

- ```
  const circle = {
      radius: 1,
      draw() {
          console.log('draw');
      }
  }
  ```

for (let key in circle)
console.log(key, circle[key])

````

The above code is used to iterate over the properties in the object.

- ```
for(let key of circle)
    console.log(key)
````

The above code will give an error. To solve it we have circle.keys() method to iterate through the keys. This method returns key as string.

- Another similar method we have Object.entries(). It returns key-value pairs as arrays.

-

```
    const circle = {
      radius: 1,
      draw() {
          console.log('draw');
      }
    };


    const another = {};

    for(let key in circle)
    another [key] = circle[key];

    //above for loop code is similar to the below one

    const another1 = Object.assign({}, circle);

```

- If we want to add addition property to the properties we get from the circle object, it is like this:

```

const another = Object.assign({
color: 'yellow'
}, circle);

```

- Yet another way to clone an object is as follows:

```

const another = {...circle};

```

This is called the spread operator.

- Built-in objects: Math Object, String Object.

- Template Literals to format strings in a better way.
