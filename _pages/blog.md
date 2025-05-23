---
layout: blog-layout
title: "Blog"
permalink: /blog/
---


<!-- <div class="blog-heading" style="text-align: center;">
  <h1>Blog</h1>
  <p>Welcome to my blog, where I share thoughts and insights about WiFi localization, deep learning, and my research journey.</p>
</div> -->


<div class="blog-posts">
  <h2>Latest Posts</h2>
  {% for post in site.posts %}
    <div class="blog-post-item">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <div class="blog-post-meta">
        {{ post.date | date: "%B %d, %Y" }}
        {% if post.categories %}
          • Categories:
          {% for category in post.categories %}
            <span>{{ category }}</span>{% unless forloop.last %}, {% endunless %}
          {% endfor %}
        {% endif %}
      </div>
      <div class="blog-post-excerpt">
        {{ post.excerpt }}
      </div>
      <a href="{{ post.url | relative_url }}" class="read-more">Read More</a>
    </div>
  {% endfor %}
</div>
