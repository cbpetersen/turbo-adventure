---
layout: post
title: "OpenGL pong, controlled through arduino"
date: 2011-06-27 07:51:19
tags: Games C# Unity3d
featuredImage: "ardujoystick1.png"
comments: true
published: true
featured: 3
---


Project from last summer, created to fool around with OpenGL and the concept of using particles to everything, the game it self is really simple, but I made it so the ball explode when a player fail to return it, likewise does the line on the field explode if the game isn't started shortly after a goal. To control the game I made a homemade game pad, consisting of two potentiometers, hooked up to my Arduino, and sent serial data to the game.

The scoreboards are made up as a seven-segment display and were a lot of fun to make.

I took a small video of the game, but it ran a crappy slow with the screen recorder running.

<video width="600" controls="controls"><source src="{{"/assets/content/pong.mp4" | prepend: site.baseurl }}" type="video/mp4" /></video>

![ardujoystick1]({{ site.baseurl }}/assets/img/ardujoystick1.png){:class="medium media"}

![ardujoystick2]({{ site.baseurl }}/assets/img/ardujoystick2.png){:class="medium media"}
