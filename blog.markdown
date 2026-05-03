---
layout: default
title: Build Log
permalink: /blog/
---


<header class="page-header">
  <div class="page-header__inner">
    <a class="page-back-link" href="/">← home</a>
    <h1>Build log</h1>
    <p class="page-header__subtitle">Development notes from building OpenSurf, an open-source surf forecasting tool.</p>
  </div>
</header>

<section class="post-list">
  <div class="wrapper">
    <ul>
      {% for post in site.posts %}
      <li class="post-list-item">
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
      </li>
      {% endfor %}
    </ul>
  </div>
</section>