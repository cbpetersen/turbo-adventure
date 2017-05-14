---
layout: post
title: "Tetris machine learning api"
date: 2016-09-15 22:14:13
tags: Games C#
featuredImage: "tetris-term.png"
comments: true
published: true
featured: 1
---

In order to separate the learning from the game engine it self i created a nodejs app for this purpose, this also allows the engine to be distributed to multiple computers to allow faster learning

the api is written to be generic and will allow different games and algorithms and uses mongoDb for storage

![tetris-term]({{ site.baseurl }}/assets/img/tetris-term.png){:class="medium media"}


Code can be found on <a href="https://github.com/cbpetersen/tetris-ml-evolutionary-api" target="_blank">Github</a>
