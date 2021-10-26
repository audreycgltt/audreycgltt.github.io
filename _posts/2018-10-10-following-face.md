---
layout: post
title:  "Following smiling face camera"
date:   2018-10-10 15:39:40
preview: /assets/img/projects/following-face/following-face-thumb.png
tags: [C++, Arduino, RaspberryPi, LEDs]
---


The goal was to create a camera that would be able to follow a face with a simple GUI in order to learn to use OpenCV and Qt using C++.

![gui screenshot](/assets/img/projects/following-face/gui-screenshot.png)

A piHAt with an LEDs matrix was showing if the spotted person (in the case there was only one in the camera range) was smiling or not. 

Tha application was running on a Raspberry Pi, face captured with a raspicam, and the servo motors were moved using an Arduino. Only smiling faces are followed!

![smiling face matrix](/assets/img/projects/following-face/following-face-thumb.png) ![sad face matrix](/assets/img/projects/following-face/sad-face.png)