---
layout: post
title: "Unity3d Pong"
date: 2011-06-27 07:51:19
tags: Games C# Unity3d
comments: true
published: true
featured: 3
---

I made this small sample project to get familiar with basic stuff like, collision and player movement etc.

<div class="media" id="webPlayerFrame"></div>

<script language="javascript" type="text/javascript">
  function startUnity() {
    document.getElementById('webPlayerFrame').innerHTML = {{ '"<iframe id=myFrame name=myFrame src=/assets/content/WebPlayer_pong.html marginheight=0 frameborder=0 height=450 width=625 scrolling=no><\/iframe><p style=font-size:small;text-align:center><<a class=\"media\" href=javascript:stopUnity(); title=Close the game\">Close the game<\/a>><\/p>"' }}
  }
  function stopUnity() {
    document.getElementById('webPlayerFrame').innerHTML = {{' "<a href=\"javascript:startUnity();\"><img id=\"Img1\" alt=\"Unity Web Player.\" src=\" /assets/img/unitypong.PNG\" width=\"600\" height=\"450\" /><\/a>"' }}
  } stopUnity()
</script>