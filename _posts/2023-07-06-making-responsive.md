---
layout: post
title: "Feedback day!"
author: "Sahibee"
---

Today, I completed the design once from my end. [Here's how it went](https://dine-restaurant-ke5w0sclp-sahibkaur.vercel.app/). But the biggest mistake I made was that I had no patience. So, instead of making each section responsive on all screen types and then moving forward, what I did was, I did the mobile view first and then completed the desktop view. This approach had following issues:
- The code got too redundant in the CSS file.
- The mid range screen sizes got ingnored i.e., the design behaved weird when I tried to resize the screen.
- Trying to fix the responsiveness became overwhelming.

And as I was overwhelmed with where to start fixing, I reached out and Jerry came to the rescue. He explained some tricks and how I can improve in a call. Here are the call notes.
- See each section as a bigger picture, like a section which has sub-sections, and further if each sub-section has other sub-sections.
- Don't look at each section with the content you see in design, just sections with demo content.
- Don't code the whole page at one screen size at once.
- Make each portion responsive and then move forward to the next.
- Use CSS variables [for colors at least].
- Use separate CSS files for styles of each reusable components like buttons.
- Have separate classes for spacing and layout if we are using reusable components/blocks.
- Use separate class for typography (colors, font-family) for reusability and reducing the complexity of code.
- Don't just use random breakpoints for media queries but rather use [Bootstrap breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/).
- Also, don't be overwhelmed if the CSS files are lengthy, they are supposed to be lengthy, so let it be but it can be optimzed by finding other solutions.

Now, I will work on all these key points and fix the code.

That's all for today.

Toodles!