---
layout: post
title: "The second task and filling in on the lost days"
author: "Sahibee"
---

Hello!
I've been missing my blogs for a few days but not the work though. I am here to announce to my fans here that I completed my first task with flying colors. Although, my mentor mentioned a bunch of improvements - that I'll list down.

>There are some minor inconsistencies in the UI, functionality and some redundancies in the code, but we skip as we have spent enough time on this already. Here are a gist of things that you can keep in mind in next tasks:

> - Try using the BEM convention
> - Remove internal CSS and use external style.css
> - Use CSS variables for colors/fonts etc.
> - Remove inconsistent spacing in code (use some tool like prettier to automate this) to make it more readable
> - Some repeated/overridden code in JS file and variables can be made for repetitive things
> - Function/variable names (try using more meaningful ones) and casing (camelCasing is preferred in JS). Avoid using keywords as variable names.
> - Try to structure your code in a better way. Keep related code together.
> - You can merge the main branch with latest code and update the vercel deployment on main url

> - I think now you would be having better understanding of creating fluid/responsive layouts. Additionally, I think you will better be able to estimate the next tasks. 

> - I hope you have learnt well from this task. How about starting with next one.

Here's the [link to the task](https://www.frontendmentor.io/challenges/tip-calculator-app-ugJNGbJUX), and this was [my final version](https://tip-calculator-gyz4jki21-sahibkaur.vercel.app/).

Then I started with [my next task](https://www.frontendmentor.io/challenges/dine-restaurant-website-yAt7Vvxt7).

I had an issue in the beginning, I applied margin to the child element but it gave margin to the parent as well. So, Jerry came to the rescue and gave the solution that I need to make the container `flex`. Here's the [deployed version of that issue](https://dine-restaurant-nu.vercel.app/).
 ![issue-1](./images/issue-1.png)

 After that I worked on the mobile view. I wanted to have something like this:
 ![circle-line][./images/circle-line.png]
 So, I try adding text for that, but it didn't quite work out.
 ![try-1][./images/try-1.png]

 But Amanjot gave the solution that I should create a div for circle and an hr tag for the line. And I completed the mobile view version _only_. Have a look](https://dine-restaurant-ra3jftdi7-sahibkaur.vercel.app/).

 There's still the issue of separator lines being too bold and ofcourse the desktop view.
 I will continue on it tomorrow.
 Till then, signing off.
 _Sahibee_
