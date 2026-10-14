---
layout: post
title: Responsive buttons
subtitle: pixel is cute! 
tags: [test]
comments: true
mathjax: true
author: Yasha COhen
---

**Responsive Buttons**

I was assigned a project where I had to turn on a new light on my led every time a button is pressed, and turn that light off as soon as the button is unpressed. This assignment had a couple of hurdles, and so my solutions are as follows:
1. Make sure any random variables that you need in multiple if statements or while loops are declared at the top. If those are declared in brackets, they mean nothing outside the brackets
2. In a sort of opposite warning, make sure to put variables that need to update in the loop. I tried to declare a state variable that was assigned to read a button input at the top of my code. That goes in the loop.
3. To model a button, attach an alligator clip to A10 and then the expansion ports. When it's connected, the button is pressed. Otherwise, the button is unpressed. 
