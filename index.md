---
layout: default
title: Hole Digging
---

<div class="news-and-buttons">
  <div class="news-section">
    <h2>📰 Latest News</h2>
    <ul>
      {% for post in site.posts limit:3 %}
        <li>
          <strong>{{ post.date | date: "%B %d, %Y" }}</strong><br />
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </li>
      {% endfor %}
    </ul>
  </div>

  <div class="button-section">
    <a href="https://store.steampowered.com/app/YOUR_GAME_ID" class="btn steam">Steam</a>
    <a href="https://youtube.com/YOUR_TRAILER_LINK" class="btn trailer">Trailer</a>
    <a href="https://discord.gg/YOUR_DISCORD" class="btn discord">Discord</a>
  </div>
</div>

<h1>📜 About This Game</h1>

<div class="about-section">

  <div class="panel">
    <p><strong>Hole Digging</strong> is a game where you dig deeper into a forgotten planet with the help of the Blerb machines, harvest resources, and create a thriving robotic city.</p>
  </div>
   
  <div class="panel">
    <img src="https://placehold.co/800x600?text=Click+to+Dig&font=roboto" alt="Click to Dig Image" style="width:100%; border-radius: 6px 6px 0 0;">
  <h2>Click to dig</h2>
    <p>Who put that hole there? We don't know! But it is filled with precious materials that can be dug out and used on your city. But dig too deep... and something might dig back.</p>
  </div>


  <div class="panel">
    <img src="https://placehold.co/800x600?text=We+Need+More+Power&font=roboto" alt="We Need More Power Image" style="width:100%; border-radius: 6px 6px 0 0;">
  <h2>We need more power</h2>
    <p>To obtain more Blerbots we need more CPU units. Use your resources to grow taller, dig harder, and get yourself an army of Blerbing machines. They love to dig, they love to shoot; all they want is to work till the hole is dry.</p>
  </div>


  <div class="panel">
    <img src="https://placehold.co/800x600?text=Find+Your+Own+Way+Down&font=roboto" alt="Find Your Own Way Down Image" style="width:100%; border-radius: 6px 6px 0 0;">
  <h2>Find Your Own Way Down</h2>
    <p>Hole Digging is about digging a hole and getting bigger, but getting to that point is your whole job:</p>

    <ul>
      <li>Get all the types of Blerbs you want.</li>
      <li>Strategically upgrade your city.</li>
      <li>Obtain ancient technology to gain higher intelligence.</li>
      <li>Understand the world around you and the secrets hidden below.</li>
      <li>Form alliances with intergalactic neighbors and welcome their visitors with open arms.</li>
    </ul>

    <p>Digging the hole is easy; digging the world is another matter.</p>
  </div>

</div>

