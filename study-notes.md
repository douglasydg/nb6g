---
layout: page
title: Study Notes
permalink: /study-notes/
---

## Study Notes

This section collects notes on propagation, tuning, operation, software, and learning progress.

{% if site.posts.size > 0 %}
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      — {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
{% else %}
<p>No notes published yet.</p>
{% endif %}
