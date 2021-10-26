---
layout: post
title:  "Talking Fridge"
date:   2019-09-04 15:39:40
preview: /assets/img/projects/talking-fridge/talking_fridge_thumb.jpg
tags: [RaspberryPi, Python, Bash, Voice]
---

Showcased at the [IFA 2019](https://b2b.ifa-berlin.com/en/) in Berlin, the intention was to demonstrate the possibilities of Snips, a vocal assistant running offline and privately, this time with a graphical interface to show the result of the interactions directly on the screen applied for a connected home, Snips for Home Appliances.

We imagined a totally voice-controlled kitchen with appliances that could communicate together, possible actions included: 
* fridge & refrigerator control
* stove control 
* timers 
* shopping list
* weather

![Screen of the fridge](/assets/img/projects/talking-fridge/screenfridge.png)

The GUI has been made using Crank Software, a GUI develpment framework for embedded systems, running on a central raspberry Pi with the vocal assistant. Applications were "deployed" as daemons in order to be relaunch everytime the raspberry Pi turn on again. Audio is handled using PulseAudio, we used vibration speakers on the back to have a good voice volume for the assitant. All elements were screwed to the back of the door using 3D printed elements. 

For demonstration purposes, we also added secret buttons that could resert some parts of the system. 

![Fridge Door](/assets/img/projects/talking-fridge/snips_fridge.png)

Our magnificient fridge was used again after a translation in japanese at the [CEATEC](https://archive.ceatec.com/2019/ja/) in October 2019.