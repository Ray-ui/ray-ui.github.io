---
layout: blog-post
title: "Why Uncertainty Matters in Wireless Localization"
excerpt: "Exploring the significance and sources of uncertainty in WiFi-based localization and its implications for research and real-world applications."
tags:
  - Localization
  - Uncertainty
  - Signal Processing
  - Deep Learning
read_time: 3
---

My research journey began with a project on uncertainty, shaped by my undergraduate training in automation. During that time, I worked on projects such as simple robot control and smart car systems, which helped me build an initial understanding of how these systems operate.

**In automation, a core idea is that control relies on feedback.** To make a good decision, we first need to know the current state of the system. With this information, we can adjust our actions and keep the system stable.

This way of thinking carried over when I moved to wireless localization. While recent work has explored using wireless signals for localization, an important question is how reliable these results are. Wireless signals are often noisy and affected by the environment, so uncertainty is unavoidable. Understanding and handling this uncertainty became the starting point of my research.

Based on this perspective, I began my first main line of research by examining uncertainty from a physical standpoint. In this work, I analyzed the sources of uncertainty at the signal level and studied how they affect localization performance ([WCNC 2023](https://ieeexplore.ieee.org/abstract/document/10118725/)).

I believe that, even in the current era of data-driven methods, such analysis remains fundamental. We should not expect models to learn patterns that are physically implausible.

Building on this, I further extended my research toward data-driven approaches. In this line of work, I explored when and why uncertainty arises in learning-based methods, and how it affects localization performance ([UBICOMP 2024](https://dl.acm.org/doi/abs/10.1145/3631437)).

This line of research led to a deeper understanding of uncertainty under both in- and out-of-distribution settings. In in-distribution regimes, uncertainty primarily arises from label noise and inherent physical ambiguity in wireless signals. In contrast, out-of-distribution scenarios introduce additional uncertainty due to distribution shifts across environments, devices, and communication conditions.
