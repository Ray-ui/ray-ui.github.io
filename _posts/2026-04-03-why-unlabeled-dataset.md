---
layout: blog-post
title: "Why We Explore Unlabeled Datasets in Wireless Localization"
excerpt: "Examining the importance of unlabeled data for scalable and practical wireless localization solutions."
tags:
  - Localization
  - Unlabeled Data
  - Deep Learning
read_time: 3
---

After exploring the role of uncertainty in wireless localization, I had the opportunity to conduct research on one of the world’s largest communication and sensing platforms. However, this also meant starting from scratch in terms of platform infrastructure and data collection. 😭

Through this process, a key insight became increasingly clear: The primary bottleneck in scaling wireless localization to real-world indoor deployment is not model design, but the availability of labeled data. In particular, each new environment requires the construction of a labeled dataset from scratch, which is both labor-intensive and difficult to generalize.

This observation naturally motivates a shift toward exploring unlabeled data.
On the one hand, real-world systems continuously generate large volumes of data during operation; on the other hand, such data can be collected at very low cost.
How to effectively leverage this abundant yet unlabeled data therefore becomes a critical and meaningful problem for wireless localization.

Our recent work explores the paradigm of pretraining and fine-tuning in <a href="https://ieeexplore.ieee.org/document/11250670" rel="noopener noreferrer">IoTJ 2025</a>, investigates unsupervised representation learning, and further examines the possibility of building localization systems without manual annotation.
