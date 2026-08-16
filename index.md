---
layout: default
title: Home
---

<div class="home-intro">
  <h1>Mehmet Eren Ahsen</h1>
  <p>Welcome to my home page. I am a faculty member working at the intersection of machine learning, healthcare, information systems, and operations.</p>
</div>

{% for post in site.posts %}
<article class="post-card">
  <div class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</div>
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
  {{ post.excerpt }}
  <p><a class="read-more" href="{{ post.url | relative_url }}">Read more</a></p>
</article>
{% endfor %}
