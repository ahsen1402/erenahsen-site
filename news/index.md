---
layout: single
title: "Publication News"
permalink: /news/
author_profile: true
---

Here you can find announcements and news about my publications, research papers, and recent scholarly work. New publication posts added to the site will appear automatically at the top of this page.

<div class="publication-news-list">
{% for post in site.posts %}
  <article class="publication-news-item">
    <div class="publication-news-date">{{ post.date | date: "%B %Y" }}</div>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    {% if post.categories %}<div class="publication-news-category">{{ post.categories | join: " · " }}</div>{% endif %}
    <p>{{ post.excerpt | strip_html | strip_newlines | truncate: 360 }}</p>
    <a class="publication-news-link" href="{{ post.url | relative_url }}">Read news <span aria-hidden="true">&#8594;</span></a>
  </article>
{% endfor %}
</div>

{% if site.posts.size == 0 %}
<p>No publication news has been added yet.</p>
{% endif %}
