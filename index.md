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

<h2>📜 About This Game</h2>

<div class="about-section">

  <p><strong>Hole Digging</strong> is a 2D incremental mining game where you dig deeper into a cursed planet, harvest strange resources, and face cosmic horrors hiding in the dark.</p>

  <p>Click to dig. Automate your mining. Upgrade your tech. Survive the unknown. Dig too deep... and something might dig back.</p>
</div>
