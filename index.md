---
layout: default
title: Hole Digging
---

<div class="buttons">
  <a href="https://store.steampowered.com/app/YOUR_GAME_ID" class="btn">Steam</a>
  <a href="https://youtube.com/YOUR_TRAILER_LINK" class="btn">Trailer</a>
  <a href="https://discord.gg/YOUR_DISCORD" class="btn">Join Discord</a>
</div>

<h2>📰 Latest News</h2>
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <strong>{{ post.date | date: "%B %d, %Y" }}</strong><br />
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<h2>📜 About This Game</h2>

<p><strong>Hole Digging</strong> is a 2D incremental mining game where you dig deeper into a cursed planet, harvest strange resources, and face cosmic horrors hiding in the dark.</p>

<p>Click to dig. Automate your mining. Upgrade your tech. Survive the unknown. Dig too deep... and something might dig back.</p>
