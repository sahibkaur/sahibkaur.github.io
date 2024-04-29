---
layout: post
title: "Training day 17 - JavaScript Basic to Beginners"
author: "Sahibee"
---

Heloo people!!

In an exercise, we were asked to create objects using factorfunction and constructor function. Following is the code for it.

```
const address = createAddress('a', 'b', 'c');


//Factory Function

function createAddress(street, city, zipcode) {
    return{
        street,
        city,
        zipcode
    };
}

//Constructor Function

let address1 = new Address('a', 'b', 'c');

function Address(street, city, zipCode) {
    this.street = street;
    this.city = city;
    this.zipCode = zipCode;
}
```
