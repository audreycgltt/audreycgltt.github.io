---
layout: post
title:  "Led Matrix Maker"
date:   2020-01-15 15:39:40
preview: /assets/img/projects/led-matrix-maker/led_matrix_thumb.png
tags: [LEDs, Python, Qt]
---

This idea came to me while I wanted to use a 8x8 red LEDs matrix with one of my raspberryPi (didn't have any simple microcontroller with me at this time) and controlling with Pyhton. I was really fustrated because I couldn't find any solution to generate animation codes automatically.
 
So it was a perfect occasion to make my first "real" application with Qt! 

![interface](/assets/img/projects/led-matrix-maker/led_matrix_window.png)

I can create an animation with many frames and it generates a Python-useable array with corresponding bytes.