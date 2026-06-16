---

permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:

* /about/
* /about.html

---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<style>
.page__content {
  line-height: 1.72;
}

.intro-card {
  margin: 0.2rem 0 2.1rem;
  padding: 1.15rem 1.25rem;
  border: 1px solid #e9e9e9;
  border-radius: 14px;
  background: linear-gradient(180deg, #ffffff 0%, #fbfbfb 100%);
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.035);
}

.intro-card p {
  margin-bottom: 0.65rem;
  color: #444;
}

.intro-card strong {
  color: #222;
}

.intro-subtle {
  color: #666;
  font-size: 0.96rem;
}

.contact-line {
  margin-top: 0.7rem;
  font-size: 0.95rem;
  color: #555;
}

.contact-line a {
  color: #444;
  text-decoration: none;
  border-bottom: 1px solid #d8d8d8;
}

.contact-line a:hover {
  color: #111;
  border-bottom-color: #999;
}

.research-tags {
  margin-top: 0.8rem;
}

.research-tags span {
  display: inline-block;
  margin: 0.12rem 0.22rem 0.12rem 0;
  padding: 0.16rem 0.56rem;
  border-radius: 999px;
  font-size: 0.74rem;
  color: #555;
  background: #f7f7f7;
  border: 1px solid #e8e8e8;
}

.paper-box {
  margin-bottom: 1.35rem;
  padding: 0.95rem;
  border: 1px solid #e9e9e9;
  border-radius: 12px;
  background: #fff;
  box-shadow: 0 1px 7px rgba(0, 0, 0, 0.035);
  transition: box-shadow 0.18s ease, transform 0.18s ease, border-color 0.18s ease;
}

.paper-box:hover {
  border-color: #dddddd;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.055);
  transform: translateY(-1px);
}

.paper-box-image img {
  border-radius: 8px;
  border: 1px solid #eeeeee;
  background: #fafafa;
}

.badge {
  display: inline-block;
  margin-bottom: 0.45rem;
  padding: 0.16rem 0.52rem;
  border-radius: 999px;
  font-size: 0.72rem;
  font-weight: 600;
  color: #555;
  background: #f4f5f7;
  border: 1px solid #e7e8ea;
  letter-spacing: 0.01em;
}

.paper-box-text {
  line-height: 1.62;
}

.paper-box-text a {
  text-decoration: none;
}

.paper-box-text a:hover {
  text-decoration: underline;
}

.note {
  color: #666;
  font-size: 0.9rem;
}

.section-divider {
  height: 1px;
  margin: 1.8rem 0 1.2rem;
  background: #eeeeee;
}
</style>

<span class='anchor' id='about-me'></span>

<div class="intro-card" markdown="1">

I am currently with the **Meituan LongCat Team**, working on **unified multimodal models**.

<span class="intro-subtle">My recent work focuses on multimodal representation learning, unified understanding-generation systems.</span>

<div class="contact-line">
Contact: <a href="mailto:haihuangcode@outlook.com">haihuangcode@outlook.com</a>
</div>

<div class="research-tags">
<span>Multimodal Learning</span>
<span>Unified Multimodal Models</span>
<span>Cross-modal Generalization</span>
<span>Understanding & Generation</span>
</div>

</div>

# Publications

<span class="note">* indicates equal contribution.</span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='../images/Achieving Cross Modal Generalization with Multimodal Unified Representation_overview.png' alt="CMG" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Achieving Cross Modal Generalization with Multimodal Unified Representation](https://proceedings.neurips.cc/paper_files/paper/2023/hash/c89f09849eb5af489abb122394ff0f0b-Abstract-Conference.html)

Yan Xia*, **Hai Huang***, Jieming Zhu, Zhou Zhao

[Project](https://github.com/haihuangcode/CMG) <strong><span class='show_paper_citations' data='FKvBzQwAAAAJ:u5HHmVD_uO8C'></span></strong>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='../images/URMMDG_framework.jpg' alt="URMMDG" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bridging Domain Generalization to Multimodal Domain Generalization via Unified Representations**

**Hai Huang**, Yan Xia, Sashuai Zhou, Hanting Wang, Shulei Wang, Zhou Zhao

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='../images/OSCMG_framework.jpg' alt="OSCMG" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Open-set Cross Modal Generalization via Multimodal Unified Representation**

**Hai Huang**, Yan Xia, Shulei Wang, Hanting Wang, Minghui Fang, Shengpeng Ji, Sashuai Zhou, Tao Jin, Zhou Zhao

[Project](https://github.com/haihuangcode/CMG/tree/master/ICCV25-OSCMG)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 Findings</div><img src='../images/ACL2025_TOC.jpg' alt="TOC" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Enhancing Multimodal Unified Representations for Cross Modal Generalization**

**Hai Huang***, Yan Xia*, Shengpeng Ji, Shulei Wang, Hanting Wang, Minghui Fang, Jieming Zhu, Zhenhua Dong, Sashuai Zhou, Zhou Zhao

[Project](https://github.com/haihuangcode/CMG/tree/master/ACL25-FCID%26TOC)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2025</div><img src='../images/icassp2025_framework.jpg' alt="Semantic Residual" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Semantic Residual for Multimodal Unified Discrete Representation](https://arxiv.org/pdf/2412.19128.pdf)

**Hai Huang**, Shulei Wang, Yan Xia

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2025 Findings</div><img src='../images/Overcoming both Domain Shift and Label Shift for Referring Video Segmentation.jpg' alt="RVS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Overcoming both Domain Shift and Label Shift for Referring Video Segmentation](https://aclanthology.org/2025.findings-naacl.167.pdf)

**Hai Huang**, Sashuai Zhou, Yan Xia

</div>
</div>

# Honors

* *2025.10* National Scholarship
* *2021.10* First Prize, [RoboMaster Robotics Competition](https://www.robomaster.com)

# Education

* *2023.09 - 2026.03*, M.S. in Artificial Intelligence, Zhejiang University
* *2019.09 - 2023.06*, B.S. in Computer Science and Technology, Northeastern University, China

# Experience

* *2025.01 - 2025.07*, Huawei, pretraining a 6B-parameter image generation model based on DiT
