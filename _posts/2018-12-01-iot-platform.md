---
layout: post
title:  "IoT Platform"
date:   2018-12-01 15:39:40
preview: /assets/img/projects/iot-platform/iot-platform-thum.png
---


Showcase platform aimed to connect to different types of sensors (temperature, humidity, etc) and retrieve their values when needed.

In the beginning, the platform was supposed to be controlled by a mobile app but I thought that voice control would be more fun. So, the voice application was powered by Snips on a raspberry pi, values requests and results were sent via MQTT using the raspi as the broker and some esp32 (programmed with Arduino IDE) publishing and subscribing to messages.
