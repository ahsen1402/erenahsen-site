---
layout: single
title: "Publication News"
permalink: /news/
author_profile: false
---

# Publication News

A running collection of research and publication news. New entries are added automatically from the site's publication posts.

{% for post in site.posts %}
  {% if post.categories contains 'research' %}
  <article style="margin-bottom: 2.5rem;">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    {% if post.date %}<p><em>{{ post.date | date: "%B %-d, %Y" }}</em></p>{% endif %}
    <p>{{ post.excerpt | strip_html | truncate: 300 }}</p>
    <a href="{{ post.url | relative_url }}">Read more →</a>
  </article>
  {% endif %}
{% endfor %}
