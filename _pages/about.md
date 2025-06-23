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

<span class='anchor' id='about-me'></span>

I am a 4th-year PhD student at the College of Computer Science, Zhejiang University, advised by Professor [Jianke Zhu (朱建科)](https://person.zju.edu.cn/en/jkzhu).

My research interests include human reconstruction, hand estimation and reconstruction, human pose generation, and portrait video generation. I have published several papers as the first author, with acceptances at AAAI, ICLR, 3DV.


# 🔥 News
- *2025.02*: &nbsp;🎉🎉 Paper accepted by ICLR 2025!
- *2024.03*: &nbsp;🎉🎉 Paper accepted by AAAI 2024!



# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/humandit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HumanDiT: Pose-Guided Diffusion Transformer for Long-form Human Motion Video Generation](https://arxiv.org/abs/2502.04847)

**Qijun Gan**, Yi Ren, Chen Zhang, Zhenhui Ye, Pan Xie, Xiang Yin, Zehuan Yuan, BINGYUE PENG, Jianke Zhu

[**Project**](https://agnjason.github.io/HumanDiT-page/)
- HumanDiT is a new pose-guided Diffusion Transformer (DiT) framework for human motion video generation. It addresses challenges in fine-grained body rendering, resolution flexibility, and visual consistency by leveraging a large-scale dataset and advanced architectural design. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 (Spotlight)</div><img src='images/pianomotion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PianoMotion10M: Dataset and Benchmark for Hand Motion Generation in Piano Performance](https://arxiv.org/abs/2406.09326)

**Qijun Gan**, Song Wang, Shengtao Wu, Jianke Zhu

ICLR 2025 (*Spotlight* - Top 5%)

[**Project**](https://agnjason.github.io/PianoMotion-page) <strong><span class='show_paper_citations' data='qZvhvPcAAAAJ:d1gkVwhDpl0C'></span></strong> [![img](https://img.shields.io/github/stars/agnJason/PianoMotion10M?style=social)](https://github.com/agnJason/PianoMotion10M)
- PianoMotion10M is a new benchmark for piano-hand motion generation, providing guidance on hand movements and fingerings in piano playing.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/xhand.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[XHand: Real-time Expressive Hand Avatar](https://arxiv.org/abs/2407.21002)

**Qijun Gan**, Zijie Zhou, Jianke Zhu

[**Project**](https://agnjason.github.io/XHand-page/) <strong><span class='show_paper_citations' data='qZvhvPcAAAAJ:2osOgNQ5qMEC'></span></strong> [![img](https://img.shields.io/github/stars/agnJason/XHand?style=social)](https://github.com/agnJason/XHand)
- XHand is a real-time expressive hand avatar designed for high-fidelity hand shape, appearance, and deformation generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/fmhr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained multi-view hand reconstruction using inverse rendering](https://ojs.aaai.org/index.php/AAAI/article/download/27946/27912)

**Qijun Gan**, Wentong Li, Jinwei Ren, Jianke Zhu

AAAI 2024

[**Project**](https://github.com/agnJason/FMHR) <strong><span class='show_paper_citations' data='qZvhvPcAAAAJ:u-x6o8ySG0sC'></span></strong>
- We propose a fine-grained multi-view hand mesh reconstruction method that leverages inverse rendering to recover detailed hand poses and textures.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3DV 2024</div><img src='images/fasthuman.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FastHuman: Reconstructing High-Quality Clothed Human in Minutes](https://arxiv.org/abs/2211.14485)

Lixiang Lin, Songyou Peng, **Qijun Gan**, Jianke Zhu

[**Project**](https://l1346792580123.github.io/nccsfs/) <strong><span class='show_paper_citations' data='qZvhvPcAAAAJ:9yKSN-GCB0IC'></span></strong>
- We introduce a fast optimization approach for high-quality clothed human body shape reconstruction from multi-view posed images.
</div>
</div>

# 🎖 Honors and Awards
- *2021.09* Outstanding Graduate (Bachelor's Degree)
- *2020.06* 2020 U.S. College Student Mathematical Modeling Contest Outstanding Prize (top 0.03%)

# 📖 Educations
- *2021.09 - 2025.02 (now)*, Ph.D. student, Zhejiang University (浙江大学), School of Computer Science and Technology.
- *2017.09 - 2021.06*, Bachelor's Degree, University of International Business and Economics (对外经济贸易大学), Information College.

# 💻 Internships
- *2025.03 - now*, [Ailibaba](https://www.alibaba.com/) <img src='images/ali.svg' style='width: 6em;'>, Research Intern, Hangzhou, China.
- *2024.07 - 2025.02*, [ByteDance](https://www.bytedance.com/en/) <img src='images/tiktok.png' style='width: 6em;'>, Research Intern, Hangzhou, China.
- *2021.10 - 2022.03*, [Huawei](https://www.huawei.com/) <img src='images/huawei.png' style='width: 2em;'>, Hangzhou, China.
