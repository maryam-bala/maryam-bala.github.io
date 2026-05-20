---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% if site.posts.size == 0 %}
  <p>No posts yet — check back soon!</p>
{% endif %}
