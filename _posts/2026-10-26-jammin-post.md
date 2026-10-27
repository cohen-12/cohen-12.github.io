---
layout: post
title: The National Anthem
subtitle: All rise
comments: true
mathjax: true
author: Yasha Cohen
---


## The National Anthem:
For this assignment, I was tasked with putting together a program that played the national anthem when a switch closed a circuit, and stopped when the switch was opened. Luckily enough, I found an excellent piece of code that contained the music for the national anthem at [this website](https://projecthub.arduino.cc/Ryaebi/us-national-anthem-with-lights-tone-167006). What I did was first read all the variable declarations, and then look for the function that was named after the national anthem. Lucky for me, this code was filled with detailed comments that really helped since I was unfamiliar with some syntax. Then, since this code contained multiple other songs, I deleted anything not referenced in the functions that play the national anthem. I briefly cut anything separate from the anthem out of the loop, variable declarations, and setup, but this was minimal. Finally, I ran the code, and it compiled. I was left with only one problem: When I turned the switch off, the music didn't stop until the end of the anthem. Since the anthem was played by running a sound function repeatedly, I edited the beginning of the sound function to return if the switch was turned off. Now, if the switch is turned off, the music stops after the current note. However, when I first tried to implement this, it didn't work at all. I had forgotten to update the relevant state variable before I checked if the switch was closed. Once I remembered this fix (which is my tip for the future: update your variables before you check them), everything ran smoothly. 
