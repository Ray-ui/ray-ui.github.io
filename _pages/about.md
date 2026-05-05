---
permalink: /
title: ""
excerpt: ""
author_profile: true
extra_css:
  - /assets/css/about-page.css
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About me

I am expected to enter the job market in 2027.

My research interests include spatial intelligence and indoor localization. 
I am advised by [Prof. Dongheng Zhang](https://scholar.google.com/citations?user=xBpvMRQAAAAJ&hl=zh-CN&oi=ao) and [Prof. Yan Chen](https://scholar.google.com/citations?user=MVOCn1AAAAAJ&hl=zh-CN) at the University of Science and Technology of China.
I am currently a research intern at JD, where I work on video understanding and temporal grounding.

<section class="news-section" aria-labelledby="news">
  <h2 id="news">News</h2>
  <div class="news-list">
    <div class="news-item">
      <time class="news-date">Jan 2026</time>
      <p>Joined JD.com as a research intern in spatial intelligence and video understanding.</p>
    </div>
    <div class="news-item">
      <time class="news-date">Nov 2025</time>
      <p>Our paper on large-scale learning-based CSI localization was accepted to IEEE IoTJ 2025.</p>
    </div>
    <div class="news-item">
      <time class="news-date">Apr 2025</time>
      <p>Released a preprint on deployment challenges in learning-based localization systems.</p>
    </div>
    <div class="news-item">
      <time class="news-date">Oct 2024</time>
      <p>Attended an academic gathering in <a href="{{ '/docs/F0D56421-F8FB-43C0-84EA-9B7FEC6D4237_1_102_a.jpeg' | relative_url }}">Melbourne</a>.</p>
    </div>
    <div class="news-item">
      <time class="news-date">Nov 2023</time>
      <p>Won Second Prize in the First Wi-Fi Sensing Contest.</p>
    </div>
    <div class="news-item">
      <time class="news-date">Oct 2023</time>
      <p>Our paper “RLoc” was accepted to IMWUT / UbiComp 2024.</p>
    </div>
  </div>
</section>
