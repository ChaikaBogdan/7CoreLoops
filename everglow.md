---
layout: page
title: Everglow
permalink: everglow
---
<iframe class="frame" width="646" height="315" src="https://www.youtube.com/embed/gWVen_-URGI" title="Everglow Trailer" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe class="frame" width="646" height="315" src="https://www.youtube.com/embed/2jkrECvRGrQ" title="Everglow OST" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe class="fill" src="https://store.steampowered.com/widget/1763150/" frameborder="0" width="646" height="190"></iframe>
<iframe class="fill" height="167" frameborder="0" src="https://itch.io/embed/1637622" width="552"><a href="https://aristarhys.itch.io/everglow">Everglow by Aristarhys</a></iframe>
<script>
(function() {
  var ratio = 16 / 9;
  var frames = document.getElementsByClassName('frame');
  for (var i = 0; i < frames.length; i++) {
    var frame = frames[i];
    var frameParent = frame.parentElement;
    var frameWidth = frameParent.clientWidth;
    var frameHeight = frameParent.clientHeight;
    frameHeight = Math.floor(frameWidth / ratio);
    frame.setAttribute('width', frameWidth);
    frame.setAttribute('height', frameHeight);
  }
  var fills = document.getElementsByClassName('fill');
  for (i = 0; i < fills.length; i++) {
    var fill = fills[i];
    var fillParent = fill.parentElement;
    fill.setAttribute('width', fillParent.clientWidth);
  }
})();
</script>
