---
layout: post
title: "Unity3d Tetris Simple AI"
date: 2011-08-26 18:43:19
tags: Games C# Unity3d
featuredImage: "Tetris600x450v100.PNG"
comments: true
published: true
featured: 3
---

Final I got time to work a little more on my Tetris AI, I started last weekend, it was incredible fun to make, the algorithm was actual pretty easy to make and only took like a night make, I haven't done a lot testing on the values that the algorithm uses, as I had an idea of making a web service that could do some statistics on collected data with different algorithm values.The online version will do anything between 50-1500 rows before dying, all depends on the blocks it will random get, and will basically only die if it gets the worst possible blocks multiple times.

The AI can only see the block its about to move, like the player can, its possible to switch auto play off, and manually place the blocks, ()move left ()move right ()Rotate () fast down. Its also possible to adjust the speed by moving the pin in the left side panel. For super speed choose full screen by right clicking the game, you exit full screen by using Esc.

{% include unity-player.html image="/assets/img/Tetris600x450v100.PNG" file="/assets/content/WebPlayer_tetris.html" height="450" width="600" %}
