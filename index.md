---
layout: splash
title: "Shaping the Digital Enterprise"
header:
  overlay_image: /assets/images/1.jpg
  overlay_filter: rgba(0, 0, 0, 0.5)
  cta_label: "Saber más"
  cta_url: "/about/"
permalink: /
---

{% include feature_row %}

{% for post in site.posts limit:4 %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
