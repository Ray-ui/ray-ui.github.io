---
layout: subpage
title: "Blogs"
permalink: /blog/
author_profile: true
extra_css:
  - /assets/css/blog-list.css
---

# Blogs

Thoughts on deep learning, wireless localization, and research.

{% for post in site.posts %}
{% include blog-card.html %}
{% endfor %}
