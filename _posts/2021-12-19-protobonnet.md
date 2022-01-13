---
layout: post
title:  "Protobonnet - Connected Santa Hat"
date:   2021-12-19 19:00:00
preview: /assets/img/projects/protobonnet/in_love_photo_thumb.jpg
tags: [esp32, LEDs, electronics, C++, sewing]
---


What is it? A connected Santa Claus hat! 

What is it called? Le ProtoBonnet!

Why? This hat has been created entirely for the [Noël des protopotes](https://www.protopotes.stream/noel/) a special livestream event that happened on the 27th of December, 2021.

![Kat and Ioio](/assets/img/projects/protobonnet/photo_live_kat_and_ioio.png) *Kathleen and Alain, the two hosts of the event!*

![protobonnet idle](/assets/img/projects/protobonnet/idle_face.png) *Prototyping time...*

## But, why?

For their first collaboration, Les protopotes decided to organised a christmas twitch stream. The live is hosted by [Neodyme](https://www.twitch.tv/ioodyme) and [Kathleen](https://www.twitch.tv/KathleenFabric) (aka Daddy and Mommy Christmas) from Switzerland. The goal was to create 6 connected costume parts that could interact with the live and people in the chat. 

I was part of the team making Kathleen's hat, along with [Tix le Geek](https://tixlegeek.io/) and [Hippo](http://les-ateliers-de-hippo.fr/).

We had the idea to create a hat with two eyes and white fabric in orter to change its color while reacting to events, and also launch two quizzes directly on twitch. 

I was personnally charged to sew the hat, make the electronics and program it in order for it to react to MQTT messages.

Viewers can trigger actions and commands through a dedicated web interface in exchange of protopoints (currency created for the event that can be obtained in exchange of Twitch channel points).

## Different faces

With two beautiful eyes and a "body" full of RGB LEDs, the hat had the perfect equipment to have multiple expressions!

#### Iddle mode
![protobonnet iddle live](/assets/img/projects/protobonnet/photo_live_iddle.png) 

Default state, a slow gliding rainbow and simple blinking eyes.

#### Love mode
![protobonnet in love](/assets/img/projects/protobonnet/in_love_photo.jpg) 

People were able to send love to the hat, it reacts accordingly by showing love too!

#### Angry face
![protobonnet angry](/assets/img/projects/protobonnet/photo_live_angry.png) 

A special face that was triggered only when a particular Twitch emote was used in the chat! Eyes frowned and animation went in fire! 

#### Sleep mode
![protobonnet asleep](/assets/img/projects/protobonnet/photo_live_sleep.png)

Like humans, hats get bored too. When nobody triggered a special command for the hat during a certain amount of time, it fell asleep waiting to be awakened again later.

#### RGB Quizz
![protobonnet asleep](/assets/img/projects/protobonnet/photo_live_quizz.png)

Quiz time: a random color was chosen and appeared on the hat, the viewers had to choose a value from 0 to 360 according to what they thought the color displayed. The closest person was winning Protopoints!

#### Shitty Flute Quizz
![protobonnet asleep](/assets/img/projects/protobonnet/photo_live_flute.png)

Another quiz for the viewers: a famous song was played in a [shitty flute](https://www.youtube.com/watch?v=L18fPGfPjlU) version and people had to find the name of the song to make it stop! In order for the hat to be as horrible as the sound, the hat had a full stroboscopic effect at full brightness. 

## Want to know more?

You can find the code on [github](https://github.com/audreycgltt/protobonnet) or you can still watch the replay of the stream on [youtube](https://youtu.be/9FJjUF4rxCs?t=2058)!

