---
layout: promo
permalink: lost-days
---
<style>
  @font-face {
    font-family: "neon-sans";
    src: url("/assets/lost_days/NeonSans.ttf");
  }
  .container {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100vw;
    height: 100vh;
  }
  .background {
    object-fit: cover;
    position: fixed;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    z-index: -1;
    width: 100vw;
    height: 100vh;
  }
  .header {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .title {
    color: white;
    font-family: 'neon-sans';
    background-color: #ffff99;
    background-size: 100%;
    background-clip: text;
    animation: glow 1s ease-in-out infinite alternate;
    text-fill-color: transparent;
    -webkit-background-clip: text;
    -moz-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-text-fill-color: transparent;
    -webkit-animation: glow 1s ease-in-out infinite alternate;
    -moz-animation: glow 1s ease-in-out infinite alternate;
    margin-bottom: 0;
  }
  @-webkit-keyframes glow {
    from {
      text-shadow: 0 0 5px #ff9000, 0 0 10px #ff9000, 0 0 15px #ff9000, 0 0 20px #ff9000, 0 0 25px #ff9000, 0 0 30px #ff9000, 0 0 35px #ff9000;
    }
    to {
      text-shadow: 0 0 10px #ff9000, 0 0 20px #ff9000, 0 0 30px #ff9000, 0 0 40px #ff9000, 0 0 50px #ff9000, 0 0 60px #ff9000, 0 0 70px #ff9000;
    }
  }
  .subtitle {
    color: white;
    font-family: 'neon-sans';
  }
</style>
<div class="container">
  <video class="background" autoplay loop muted poster="/assets/lost_days/vortex.jpg">
    <source src="/assets/lost_days/vortex.mp4" type="video/mp4">
  </video>
  <div class="header">
    <h1 class="title">EVERGLOW</h1>
    <h2 class="subtitle">THE LOST DAYS</h2>
  </div>
  <div>
</div>
