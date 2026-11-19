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

I am a third-year master’s student at China University of Geosciences (Wuhan), advised by Prof. [Kun Sun](https://grzy.cug.edu.cn/sunkun/zh_CN/index.htm). I received my bachelor’s degree from China University of Geosciences (Wuhan) in 2024. My research interests include 3D/4D vision, embodied spatial intelligence, and 4D video world models.

# 🔥 News
- *2026.10*: &nbsp;🎉🎉 One Paper has been accepted by Pattern Recognition (CCF B)
- *2026.05*: &nbsp;🎉🎉 One Paper has been accepted by TCSVT2026 (CCF B, IF=8.4)
- *2025.08*: &nbsp;🎉🎉 One Paper has been accepted by ACM MM2025 (CCF A)

# 📝 Publications 

<h2 class="pub-category" id="3d-vision">3D Vision</h2>

<div class="pub-group">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/paper_img/MonoGeoDreamer.jpg' alt="MonoGeoDreamer" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

MonoGeoDreamer: Reading Geometry from a Frozen Text-to-Image Generator

**Yu Liu**, Kun Sun$^{*}$

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pattern Recognition</div><img src='images/paper_img/Control2Geo.png' alt="Control2Geo" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

Control2Geo: Monocular Geometry Estimation with Diffusion-Based Controller Priors

**Yu Liu**, Kun Sun$^{*}$, KunQian Li, Chang Tang, Yuhua Qian

[**Code**](https://github.com/Lioely/Control2Geo) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT2026</div><img src='images/paper_img/TextBridgeDepth.png' alt="TextBridgeDepth" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

TextBridgeDepth: A Text-Guided Latent Diffusion Bridge Model for Monocular Depth Estimation

**Yu Liu**, Kun Sun$^{*}$, KunQian Li, Chang Tang, Yuhua Qian

[**Paper**](https://ieeexplore.ieee.org/abstract/document/11614007) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM2025</div><img src='images/paper_img/TPDepth-acmmm2025.png' alt="TPDepth" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

TPDepth: Leveraging Text Prompts with ControlNet to Boost Diffusion-based Depth Estimation

**Yu Liu**, Kun Sun$^{*}$, Chang Tang, Yuhua Qian, Xin Li

[**Paper**](https://dl.acm.org/doi/10.1145/3746027.3755384)  [**Code**](https://github.com/Lioely/TPDepth) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>
<button type="button" class="paper-more-toggle" hidden>Show more</button>
</div>

<h2 class="pub-category" id="low-light-vision">Low light vision</h2>

<div class="pub-group">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/paper_img/RePriFusion.png' alt="RePriFusion" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

RePriFusion: Retinex-Based Low-Light Image Enhancement via Prior-Specific Fusion

**Yu Liu**, Kun Sun$^{*}$, KunQian Li, Chang Tang, Qingshan Xu

</div>
</div>
<button type="button" class="paper-more-toggle" hidden>Show more</button>
</div>

<script>
document.querySelectorAll('.pub-group').forEach(function (group) {
  var papers = group.querySelectorAll('.paper-box');
  var button = group.querySelector('.paper-more-toggle');
  if (!button || papers.length <= 5) return;
  var extra = Array.prototype.slice.call(papers, 5);
  var expanded = false;
  extra.forEach(function (paper) { paper.hidden = true; });
  button.hidden = false;
  button.setAttribute('aria-expanded', 'false');
  button.addEventListener('click', function () {
    expanded = !expanded;
    extra.forEach(function (paper) { paper.hidden = !expanded; });
    button.setAttribute('aria-expanded', expanded ? 'true' : 'false');
    button.textContent = expanded ? 'Show less' : 'Show more';
  });
});
</script>


# 🎖 Honors and Awards
- 2026.10 National Scholarship
- 2024.06 Kaggle: Image Matching Challenge 2024-Hexathlon(69/929 Bronze Medal🥉)
- 2023.06 Kaggle: Image Matching Challenge 2023(38/494 Silver Medal🥈)
- 2022.10 Kaggle: RSNA 2022 Cervical Spine Fracture Detection(29/883 Silver Medal🥈)


# 📖 Educations
- *2024.09 - now*,  China University of Geosciences (Wuhan)
- *2020.09 - 2024.06*,  China University of Geosciences (Wuhan)
