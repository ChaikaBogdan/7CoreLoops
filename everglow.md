---
layout: page
title: Everglow
permalink: everglow
---
<iframe class="frame" width="646" height="315" src="https://www.youtube.com/embed/gWVen_-URGI" title="Everglow Trailer" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe class="frame" width="646" height="315" src="https://www.youtube.com/embed/2jkrECvRGrQ" title="Everglow OST" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe id="steam" src="https://store.steampowered.com/widget/1763150/" frameborder="0" width="646" height="190"></iframe>
<script>
(function() {
  var ratio = 16 / 9;
  var iframes = document.getElementsByClassName('frame');
  for (var i = 0; i < iframes.length; i++) {
    var frame = iframes[i];
    var frameParent = frame.parentElement;
    var frameWidth = frameParent.clientWidth;
    var frameHeight = frameParent.clientHeight;
    frameHeight = Math.floor(frameWidth / ratio);
    frame.setAttribute('width', frameWidth);
    frame.setAttribute('height', frameHeight);
  }
  var steam = document.getElementById('steam');
  var steamParent = steam.parentElement;
  steam.width = steamParent.clientWidth;
})();
</script>
