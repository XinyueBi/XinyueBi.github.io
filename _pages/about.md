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

Hi! My name is Xinyue Bi (毕馨月). I am currently a Master's student (MSc) in Machine Learning at [MBZUAI](https://mbzuai.ac.ae/), supervised by Prof. [Zhiqiang Shen](https://zhiqiangshen.com/) and Prof. [Jian Kang](https://jiank2.github.io/). My research interests include **dataset distillation** and **efficient learning**. I work closely with my collaborator and friend [Jiacheng Cui](https://jiachengcui.com/).

Before joining MBZUAI, I obtained my bachelor's degree in **Mathematics** from the **University of Ottawa** in 2023. I am always open to academic collaboration and discussions related to my research interests.

# 🔥 News
- *2026.09*: &nbsp;🎉🎉 *SODA* has been accepted to **NeurIPS 2026**. See you in Sydney!
- *2026.04*: &nbsp;🎉🎉 *HALD* has been accepted to **ICML 2026**. See you in Seoul!
- *2026.04*: &nbsp;🎉🎉 *LLMSurgeon* has been accepted to **ACL 2026**. See you in San Diego!
- *2025.09*: &nbsp;🎉🎉 *FADRM* has been accepted to **NeurIPS 2025**.
- *2025.08*: &nbsp;🎉🎉 I joined the Machine Learning Department at **MBZUAI** as an MSc student.


# 📝 Publications

<a href='https://scholar.google.com/citations?user=LLY-pJgAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
&nbsp;<sup>*</sup> Equal contribution

<div class="publication-scroll__hint" aria-hidden="true">
  <span>Scroll for more publications</span>
  <i class="fas fa-arrow-down"></i>
</div>
<div class='publication-scroll' markdown="1">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/soda.png' alt="SODA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SODA: Selective Optimization with Deferred BN Alignment for Efficient Dataset Distillation

**Xinyue Bi**<sup>*</sup>, Jiacheng Cui<sup>*</sup>, Yaxin Luo, Xinyi Shang, Jiacheng Liu, Xiaohan Zhao, Zhiqiang Shen

*Conference on Neural Information Processing Systems (**NeurIPS**), 2026*

*Paper coming soon* <strong><span class='show_paper_citations' data-title="SODA: Selective Optimization with Deferred BN Alignment for Efficient Dataset Distillation"></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/LLM-surgeon.png' alt="LLMSurgeon" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLMSurgeon: Diagnosing Data Mixture of Large Language Models](https://aclanthology.org/2026.acl-long.1964.pdf)

Yaxin Luo<sup>*</sup>, Jiacheng Cui<sup>*</sup>, Xiaohan Zhao, Xinyi Shang, Jiacheng Liu, **Xinyue Bi**, Zhaoyi Li, Zhiqiang Shen

*Annual Meeting of the Association for Computational Linguistics (**ACL**), 2026*

[**Paper**](https://aclanthology.org/2026.acl-long.1964.pdf) <strong><span class='show_paper_citations' data-title="LLMSurgeon: Diagnosing Data Mixture of Large Language Models"></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/FADRM.png' alt="FADRM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FADRM: Fast and Accurate Data Residual Matching for Dataset Distillation](https://arxiv.org/abs/2506.24125)

Jiacheng Cui<sup>*</sup>, **Xinyue Bi**<sup>*</sup>, Yaxin Luo, Xiaohan Zhao, Jiacheng Liu, Zhiqiang Shen

*Conference on Neural Information Processing Systems (**NeurIPS**), 2025*

[**Paper**](https://arxiv.org/abs/2506.24125) | [**Code**](https://github.com/Jiacheng8/FADRM) <strong><span class='show_paper_citations' data-title="FADRM: Fast and Accurate Data Residual Matching for Dataset Distillation"></span></strong> [![](https://img.shields.io/github/stars/Jiacheng8/FADRM?style=social&label=Stars)](https://github.com/Jiacheng8/FADRM)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/HALD.png' alt="HALD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hard Labels In! Rethinking the Role of Hard Labels in Mitigating Local Semantic Drift](https://arxiv.org/abs/2512.15647)

Jiacheng Cui, Bingkui Tong, **Xinyue Bi**, Xiaohan Zhao, Jiacheng Liu, Zhiqiang Shen

*International Conference on Machine Learning (**ICML**), 2026*

[**Paper**](https://arxiv.org/abs/2512.15647) | [**Code**](https://github.com/Jiacheng8/HALD) <strong><span class='show_paper_citations' data-title="Hard Labels In! Rethinking the Role of Hard Labels in Mitigating Local Semantic Drift"></span></strong> [![](https://img.shields.io/github/stars/Jiacheng8/HALD?style=social&label=Stars)](https://github.com/Jiacheng8/HALD)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/CV-DD.png' alt="CV-DD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dataset Distillation via Committee Voting](https://arxiv.org/abs/2501.07575)

Jiacheng Cui, Zhaoyi Li, Xiaochen Ma, **Xinyue Bi**, Yaxin Luo, Zhiqiang Shen

*arXiv preprint, 2025*

[**Paper**](https://arxiv.org/abs/2501.07575) | [**Code**](https://github.com/Jiacheng8/CV-DD) <strong><span class='show_paper_citations' data-title="Dataset Distillation via Committee Voting"></span></strong> [![](https://img.shields.io/github/stars/Jiacheng8/CV-DD?style=social&label=Stars)](https://github.com/Jiacheng8/CV-DD)
</div>
</div>
</div>

# 🎖 Honors and Awards
- **2025–2027**, MBZUAI Graduate Fellowship (Full Scholarship)

# 📖 Educations
- **2025.09 – 2027.06 (expected)**, Master of Science in Machine Learning, Mohamed bin Zayed University of Artificial Intelligence (MBZUAI), Abu Dhabi, UAE  
- **2019.09 – 2023.06**, Bachelor of Science in Mathematics, University of Ottawa, Ottawa, Canada
