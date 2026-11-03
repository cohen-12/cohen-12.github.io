---
layout: post
title: Arrays
subtitle: lists?
comments: true
mathjax: true
author: Yasha Cohen
---

**Arrays**

So, for this assignment, I had to pick an analog pin at random every second, and turn it on at a random voltage if it was previously off, or turn it off
if it was previously on. My first attempt was tricky and convoluted because I wanted to define each element of my state variable array as the result of reading
in from each pin. However, this turns out to be unnecessary if every time I turn a pin on, I update my states array, and this is what I ended up doing. This is my 
tip to my future self: you don't have to do something through code just because you can. In this case, just because I can read in from a pin doesn't mean I should.
It complicates my approach where my eventual solution is so much cleaner. 

![yo: gurt](https://cohen-12.github.io/assets/img/arrays_img.jpg){: .mx-auto.d-block :}

