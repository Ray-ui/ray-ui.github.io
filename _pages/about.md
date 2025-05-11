---
permalink: /
title: ""
excerpt: ""
author_profile: true
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

<style>
.label-paper {
    background-color: #4A90E2; /* Muted sky blue */
}

.label-conf {
    background-color: #4A90E2; /* Soft amber yellow */
}

.label-time {
    background-color: #F5A623; /* Light gray */
}
.label {
    display: inline-block;
    padding: 0.2em 0.6em 0.3em;
    font-size: 75%;
    font-weight: 700;
    line-height: 1;
    color: #fff;
    text-align: center;
    white-space: nowrap;
    vertical-align: baseline;
    border-radius: 0.25em;
}

.label-update {
    background-color: #28a745;  /* Green background */
    color: #ffffff;  /* White text */
}

/* .label {
    display: inline;
    padding: .2em .6em .3em;
    padding-top: 0.2em;
    padding-right: 0.6em;
    padding-bottom: 0.3em;
    padding-left: 0.6em;
    font-size: 80%;
    font-weight: bold;
    line-height: 1;
    color: #fff;
    text-align: center;
    white-space: nowrap;
    vertical-align: baseline;
    border-radius: .4em;
} */
</style>


<span class='anchor' id='about-me'></span>

# &#128512; About me
I specialize in WiFi localization, leveraging deep learning techniques to address challenges in indoor positioning.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- <span class='label label-update'>Mar 2025</span>:
Oh, I was just rejected by TMC. Haha. See you next time!

- <span class='label label-update'>Dec 2024</span>:
This year, I have dedicated substantial time to exploring a new platform, tackling a variety of engineering challenges 😓.
The exciting news is that a paper based on this platform has just been submitted to TMC—stay tuned for more updates!  🎉

- <span class='label label-update'>Oct 2024</span>:
I was delighted to meet everyone in Melbourne. Looking forward to our next gathering!

# &#128209; Preprint

## [Indoor Localization] [Integrated Sensing and Communication (ISAC)] [ Data-driven ] [Large-scale Deployment]

This series explores data-driven localization approaches on a large-scale ISAC platform.

<span class='label label-conf'>Submit to IOTJ</span>: [Lessons from Deploying Learning-based CSI Localization on a Large-Scale ISAC Platform](https://arxiv.org/abs/2504.17173)

This work presents some interesting challenges we encountered while deploying a learning-based localization system in a large-scale ISAC platform.

We look forward to sharing more upcoming results in this line of research.

# &#128209; Publications

## [Indoor Localization] [Channel State Information] [Angle of Arrival]

This series aims to leverage uncertainty quantification to enhance the robustness of angle-based localization.

<span class = 'label label-conf'>UBICOMP'23</span>: [RLoc: Towards Robust Indoor Localization by Quantifying Uncertainty](https://dl.acm.org/doi/abs/10.1145/3631437) 

**Tianyu Zhang**, Dongheng Zhang, Guanzhong Wang, Yadong Li, Yang Hu, Qibin Sun, Yan Chen

<span class = 'label label-conf'>WCNC'23</span>: [WiCo: Robust Indoor Localization via Spectrum Confidence Estimation](https://ieeexplore.ieee.org/abstract/document/10118725/)  
**Tianyu Zhang**, Dongheng Zhang, Shuai Yang, Qibin Sun, Yan Chen

## &#128187; Projects

- [Human-held device WiFi indoor localization dataset](https://github.com/H-WILD/human_held_device_wifi_indoor_localization_dataset): We have developed the H-WILD dataset for WiFi-based indoor localization using human-held devices. Special thanks to my collaborator, Guanzhong Wang. I welcome potential collaborations to enhance the value of this project for the community.

## &#127942; Honors and Awards

<!-- <span class = 'label label-time'> November 2023 </span> Awarded Second Prize (2nd out of 287 teams) and 100,000 CNY in the [First WiFi Sensing Contest](https://www.chaspark.com/#/live/941113361357037568?anchorV=946512265287860224&multi=zh) as the team leader. I am grateful to my partner for their collaboration and support, and I extend special thanks to Tongzhou Zhou for his invaluable guidance on my presentation. -->
- **Nov 2023**: Awarded Second Prize (2nd out of 287 teams) and 100,000 CNY in the [First WiFi Sensing Contest](https://www.chaspark.com/#/live/941113361357037568?anchorV=946512265287860224&multi=zh) as the team leader. I am grateful to my partner for their collaboration and support, and I extend special thanks to Tongzhou Zhou for his invaluable guidance on my presentation.

- **Undergraduate**:
    - Awarded the People’s First-Class Scholarship (GPA: 3.8/4.0)
    - Secured first prizes in both national and intra-university competitions
    - Recognized as a Merit Student and received the Excellent Student Cadre Award

# 📖 Educations
- *2023 - Present*, Pursuing Ph.D. in Cyberspace Security, University of Science and Technology of China
- *2021 - 2023*, M.S. in Computer Technology, University of Science and Technology of China
- *2017 - 2021*, B.S. in Automation (Excellent Engineer Program), University of Science and Technology of Beijing


<!-- # Under Construction 🚧 (/#blog.md) -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->