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
.profile-intro {
  margin-bottom: 2rem;
  line-height: 1.75;
  color: #444;
}

.profile-intro strong {
  color: #222;
}

.research-tags {
  margin-top: 0.7rem;
}

.research-tags span {
  display: inline-block;
  margin: 0.15rem 0.25rem 0.15rem 0;
  padding: 0.18rem 0.55rem;
  border-radius: 999px;
  font-size: 0.78rem;
  color: #555;
  background: #f6f6f6;
  border: 1px solid #e9e9e9;
}

.pub-card {
  display: flex;
  gap: 1rem;
  margin: 1.15rem 0 1.45rem;
  padding: 1rem;
  border: 1px solid #eaeaea;
  border-radius: 12px;
  background: #fff;
  box-shadow: 0 1px 5px rgba(0, 0, 0, 0.035);
}

.pub-card-image {
  flex: 0 0 34%;
  max-width: 34%;
}

.pub-card-image img {
  width: 100%;
  border-radius: 8px;
  border: 1px solid #eee;
  background: #fafafa;
}

.pub-card-body {
  flex: 1;
  line-height: 1.6;
}

.pub-venue {
  display: inline-block;
  margin-bottom: 0.35rem;
  padding: 0.15rem 0.48rem;
  border-radius: 999px;
  font-size: 0.72rem;
  font-weight: 600;
  color: #555;
  background: #f4f5f7;
  border: 1px solid #e7e8ea;
}

.pub-title {
  margin-bottom: 0.35rem;
  font-weight: 600;
}

.pub-authors {
  margin-bottom: 0.35rem;
  color: #555;
  font-size: 0.95rem;
}

.pub-links {
  font-size: 0.92rem;
}

.note {
  color: #666;
  font-size: 0.9rem;
}

@media (max-width: 768px) {
  .pub-card {
    display: block;
  }

  .pub-card-image {
    max-width: 100%;
    margin-bottom: 0.8rem;
  }
}
</style>

<span class='anchor' id='about-me'></span>

<div class="profile-intro" markdown="1">

I am currently with the **Meituan LongCat Team**, working on **unified multimodal models**.

Please feel free to contact me at **[haihuangcode@outlook.com](mailto:haihuangcode@outlook.com)**.

<div class="research-tags">
<span>Multimodal Learning</span>
<span>Unified Multimodal Models</span>
<span>Cross-modal Generalization</span>
<span>Understanding and Generation</span>
</div>

</div>

# Publications

<span class="note">* indicates equal contribution.</span>

<div class="pub-card">
  <div class="pub-card-image">
    <img src="{{ '/images/Achieving Cross Modal Generalization with Multimodal Unified Representation_overview.png' | relative_url }}" alt="CMG">
  </div>
  <div class="pub-card-body" markdown="1">
    <div class="pub-venue">NeurIPS 2023</div>
    <div class="pub-title" markdown="1">[Achieving Cross Modal Generalization with Multimodal Unified Representation](https://proceedings.neurips.cc/paper_files/paper/2023/hash/c89f09849eb5af489abb122394ff0f0b-Abstract-Conference.html)</div>
    <div class="pub-authors" markdown="1">Yan Xia\*, **Hai Huang\***, Jieming Zhu, Zhou Zhao</div>
    <div class="pub-links" markdown="1">[Project](https://github.com/haihuangcode/CMG) <strong><span class='show_paper_citations' data='FKvBzQwAAAAJ:u5HHmVD_uO8C'></span></strong></div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-image">
    <img src="{{ '/images/URMMDG_framework.jpg' | relative_url }}" alt="URMMDG">
  </div>
  <div class="pub-card-body" markdown="1">
    <div class="pub-venue">ICCV 2025</div>
    <div class="pub-title" markdown="1">Bridging Domain Generalization to Multimodal Domain Generalization via Unified Representations</div>
    <div class="pub-authors" markdown="1">**Hai Huang**, Yan Xia, Sashuai Zhou, Hanting Wang, Shulei Wang, Zhou Zhao</div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-image">
    <img src="{{ '/images/OSCMG_framework.jpg' | relative_url }}" alt="OSCMG">
  </div>
  <div class="pub-card-body" markdown="1">
    <div class="pub-venue">ICCV 2025</div>
    <div class="pub-title" markdown="1">Open-set Cross Modal Generalization via Multimodal Unified Representation</div>
    <div class="pub-authors" markdown="1">**Hai Huang**, Yan Xia, Shulei Wang, Hanting Wang, Minghui Fang, Shengpeng Ji, Sashuai Zhou, Tao Jin, Zhou Zhao</div>
    <div class="pub-links" markdown="1">[Project](https://github.com/haihuangcode/CMG/tree/master/ICCV25-OSCMG)</div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-image">
    <img src="{{ '/images/ACL2025_TOC.jpg' | relative_url }}" alt="TOC">
  </div>
  <div class="pub-card-body" markdown="1">
    <div class="pub-venue">ACL 2025 Findings</div>
    <div class="pub-title" markdown="1">Enhancing Multimodal Unified Representations for Cross Modal Generalization</div>
    <div class="pub-authors" markdown="1">**Hai Huang\***, Yan Xia\*, Shengpeng Ji, Shulei Wang, Hanting Wang, Minghui Fang, Jieming Zhu, Zhenhua Dong, Sashuai Zhou, Zhou Zhao</div>
    <div class="pub-links" markdown="1">[Project](https://github.com/haihuangcode/CMG/tree/master/ACL25-FCID%26TOC)</div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-image">
    <img src="{{ '/images/icassp2025_framework.jpg' | relative_url }}" alt="Semantic Residual">
  </div>
  <div class="pub-card-body" markdown="1">
    <div class="pub-venue">ICASSP 2025</div>
    <div class="pub-title" markdown="1">[Semantic Residual for Multimodal Unified Discrete Representation](https://arxiv.org/pdf/2412.19128.pdf)</div>
    <div class="pub-authors" markdown="1">**Hai Huang**, Shulei Wang, Yan Xia</div>
  </div>
</div>

<div class="pub-card">
  <div class="pub-card-image">
    <img src="{{ '/images/Overcoming both Domain Shift and Label Shift for Referring Video Segmentation.jpg' | relative_url }}" alt="Referring Video Segmentation">
  </div>
  <div class="pub-card-body" markdown="1">
    <div class="pub-venue">NAACL 2025 Findings</div>
    <div class="pub-title" markdown="1">[Overcoming both Domain Shift and Label Shift for Referring Video Segmentation](https://aclanthology.org/2025.findings-naacl.167.pdf)</div>
    <div class="pub-authors" markdown="1">**Hai Huang**, Sashuai Zhou, Yan Xia</div>
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
