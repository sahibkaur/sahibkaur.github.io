---
layout: post
title: "Training day 8 - HTML and CSS [Part 2]"
author: "Sahibee"
---


Heloo people!!

I was on the second part. I revised fonts, images, animation and forms Here are the notes:


Fonts:

- Serif, San-serif, Monospace

width: 50ch;


Clipping: We can clip an image to take the form of any shape. Just search on google “Clip an image”. Upload the image and it will give you the clip path of the shape you select.

Pseudo class selectors:
:hover
:visited
:active

CSS image filters: we can apply filters on an image, like greyscale, blur etc.

<img src=“images/meal.jpg” srcset=“
Images/meal.jpg 1x,
Images/meal@2x.jpg 2x,
Images/meal@3x.jpg 3x”>

Srcset is used to give alternate images for difference sizes.

<img src=“images/meal.jpg” srcset=“
Images/meal.jpg 400w,
Images/meal@2x.jpg 800w,
Images/meal@3x.jpg 1200w”>

To give exact value of width of the devices

<picture>
    <source media=“(max-width: 500px)” srcset=“images/meal-cropped.jpg”>
    <source media=“(min-width: 501px)” srcset=“images/meal-cropped@2x.jpg”>
    <img src=“images/meal.jpg” alt=“”>
</picture>


Forms
- <button type=“submit”>Submit</button>
- <button type=“reset”>Clear</button> 
    - It empties all the input fields.

CSS variables:
:root {
    —color-primary: #fc1232;
    —border-size: 2px;
    —border-radius: 10px;
}

That's it for today.


See ya tomorrow.
Toodles!

