---
permalink: /
title: ""
excerpt: "Hai Huang — native multimodal LLM pretraining and visual representations."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* Small, homepage-only refinements to the existing academic theme. */
html { scroll-padding-top: 76px; }
#main { max-width: 1100px; margin-top: 24px; animation: none; }
.masthead { animation: none; }
.masthead__inner-wrap { max-width: 1100px; }
.academic-home { color: #333; font-size: 15px; line-height: 1.75; }
.academic-home a { color: #24558c; text-decoration: none; }
.academic-home a:hover { color: #163b65; text-decoration: underline; }
.academic-home a:focus-visible { outline: 2px solid #24558c; outline-offset: 4px; }
.academic-home #about-me { margin: 0; }
.academic-home #about-me::before { display: none; }
.academic-home p { margin: 0 0 10px; }
.academic-home .profile-intro { margin-bottom: 12px; }
.academic-home .profile-contact { font-size: 13px; color: #666; }
.profile-contact a + a::before { content: "·"; display: inline-block; margin: 0 10px; color: #aaa; }
.profile-nav { display: flex; flex-wrap: wrap; gap: 20px; margin: 18px 0 26px; font-size: 13px; }
.profile-nav a { padding: 3px 0; }
.academic-home h2 { margin: 28px 0 12px; padding-bottom: 8px; border-bottom: 1px solid #e7e7e7; font-size: 21px; font-weight: 600; }
.academic-home h3 { margin: 0 0 5px; font-size: 15px; font-weight: 600; line-height: 1.55; }
.academic-home .section-note { margin: -4px 0 12px; color: #707070; font-size: 12px; }
.recent-work { padding: 12px 0; border-bottom: 1px solid #f0f0f0; }
.recent-work:last-child { border: 0; }
.academic-home .recent-work p { margin: 0 0 5px; color: #666; font-size: 13px; }
.work-links { display: flex; flex-wrap: wrap; gap: 16px; font-size: 12px; }
.work-links a { padding: 2px 0; }
.hh-paper { display: grid; grid-template-columns: 180px minmax(0, 1fr); align-items: center; gap: 22px; padding: 19px 0; border-bottom: 1px solid #ededed; }
.hh-paper:last-child { border: 0; }
.hh-paper-figure { display: flex; align-items: center; justify-content: center; aspect-ratio: 1.6; overflow: hidden; border: 1px solid #eee; border-radius: 4px; background: #fff; }
.hh-paper-figure img { display: block; width: 100%; height: 100%; max-height: 100%; padding: 6px; object-fit: contain; transition: transform .18s ease; }
.hh-paper:hover .hh-paper-figure img { transform: scale(1.015); }
.hh-venue { display: inline-block; margin-bottom: 5px; color: #53667c; font-size: 12px; font-weight: 600; }
.academic-home .hh-paper-authors { margin: 0; color: #666; font-size: 12px; line-height: 1.8; }
.hh-paper-authors strong { color: #333; font-weight: 600; }
.hh-paper-links { display: flex; flex-wrap: wrap; gap: 15px; margin-top: 7px; font-size: 12px; }
.hh-paper-links a { padding: 2px 0; }
.show_paper_citations { color: #666; }
.honor-list { margin: 0; padding: 0; list-style: none; }
.honor-list li { display: grid; grid-template-columns: 72px minmax(0, 1fr); gap: 12px; margin: 0; padding: 7px 0; font-size: 13px; }
.honor-list time { color: #707070; font-size: 12px; }
.academic-home footer { margin-top: 28px; padding: 14px 0 24px; border-top: 1px solid #eee; color: #737373; font-size: 12px; }
@media (max-width: 767px) {
  #main { margin-top: 16px; }
  .academic-home { font-size: 14px; }
  .academic-home h2 { margin-top: 24px; font-size: 20px; }
  .hh-paper { grid-template-columns: 140px minmax(0, 1fr); gap: 18px; }
}
@media (max-width: 560px) {
  .profile-nav { gap: 18px; margin: 12px 0 20px; }
  .hh-paper { grid-template-columns: 1fr; gap: 12px; padding: 18px 0; }
  .hh-paper-figure { aspect-ratio: 2; }
  .hh-paper-figure img { padding: 10px; }
  .academic-home .hh-paper-authors { font-size: 12px; }
  .academic-home .profile-contact { font-size: 12px; overflow-wrap: anywhere; }
  .profile-contact a + a::before { margin: 0 7px; }
}
@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
  .academic-home *, .academic-home *::before, .academic-home *::after { animation: none !important; transition: none !important; }
  .hh-paper:hover .hh-paper-figure img { transform: none; }
}
@media print {
  .masthead, .profile-nav, .academic-home footer { display: none; }
  .hh-paper, .recent-work { break-inside: avoid; }
}
</style>

<div class="academic-home">
  <div id="about-me">
    <p class="profile-intro">I am currently with the <strong>Meituan LongCat Team</strong> (<span lang="zh-CN">北斗计划</span>), working on <strong>native multimodal LLM pretraining</strong>. My research focuses on visual representations and ViT pretraining, with interests in 3D, Blender, CAD, and agentic post-training.</p>
    <p class="profile-contact"><a href="mailto:haihuangcode@outlook.com" target="_self">haihuangcode@outlook.com</a><a href="https://github.com/haihuangcode" target="_blank" rel="noopener noreferrer">GitHub</a></p>
  </div>
  <nav class="profile-nav" aria-label="Page sections">
    <a href="#recent-work" target="_self" data-ss-opts='{"offset":-76,"speed":0}'>Recent work</a>
    <a href="#publications" target="_self" data-ss-opts='{"offset":-76,"speed":0}'>Publications</a>
    <a href="#honors" target="_self" data-ss-opts='{"offset":-76,"speed":0}'>Honors</a>
  </nav>

  <section id="recent-work" aria-labelledby="recent-title">
    <h2 id="recent-title">Recent work</h2>
    <article class="recent-work">
      <h3><a href="https://longcat.ai/blog/longcat-2.5" target="_blank" rel="noopener noreferrer">LongCat-2.5: Native Multimodality for Agentic Tasks</a></h3>
      <p>Native visual modeling, agentic coding, and 3D tasks.</p>
      <div class="work-links"><a href="https://longcat.ai/blog/longcat-2.5" target="_blank" rel="noopener noreferrer">Tech blog</a><a href="https://huggingface.co/meituan-longcat/LongCat-2.5" target="_blank" rel="noopener noreferrer">Model</a></div>
    </article>
    <article class="recent-work">
      <h3><a href="https://huggingface.co/papers/2611.12426" target="_blank" rel="noopener noreferrer">dNaViT: Discrete Codes are General-Purpose Visual Representations</a></h3>
      <p>Shared discrete visual codes for understanding, generation, and editing.</p>
      <div class="work-links"><a href="https://arxiv.org/abs/2611.12426" target="_blank" rel="noopener noreferrer">Paper</a><a href="https://huggingface.co/papers/2611.12426" target="_blank" rel="noopener noreferrer">Hugging Face</a></div>
    </article>
  </section>

  <section id="publications" aria-labelledby="publications-title">
    <h2 id="publications-title">Publications</h2>
    <p class="section-note">* Equal contribution.</p>
    <article class="hh-paper">
      <div class="hh-paper-figure"><img src="{{ '/images/URMMDG_framework.jpg' | relative_url }}" alt="Framework for multimodal domain generalization using unified representations" width="640" height="400" loading="lazy" decoding="async"></div>
      <div><span class="hh-venue">ICCV 2025</span><h3>Bridging Domain Generalization to Multimodal Domain Generalization via Unified Representations</h3><p class="hh-paper-authors"><strong>Hai Huang</strong>, Yan Xia, Sashuai Zhou, Hanting Wang, Shulei Wang, Zhou Zhao</p></div>
    </article>

    <article class="hh-paper">
      <div class="hh-paper-figure"><img src="{{ '/images/OSCMG_framework.jpg' | relative_url }}" alt="Framework for open-set cross-modal generalization" width="640" height="400" loading="lazy" decoding="async"></div>
      <div><span class="hh-venue">ICCV 2025</span><h3>Open-set Cross Modal Generalization via Multimodal Unified Representation</h3><p class="hh-paper-authors"><strong>Hai Huang</strong>, Yan Xia, Shulei Wang, Hanting Wang, Minghui Fang, Shengpeng Ji, Sashuai Zhou, Tao Jin, Zhou Zhao</p><div class="hh-paper-links"><a href="https://github.com/haihuangcode/CMG/tree/master/ICCV25-OSCMG" target="_blank" rel="noopener noreferrer">Project</a></div></div>
    </article>

    <article class="hh-paper">
      <div class="hh-paper-figure"><img src="{{ '/images/ACL2025_TOC.jpg' | relative_url }}" alt="Training-free codebook optimization for multimodal representations" width="640" height="400" loading="lazy" decoding="async"></div>
      <div><span class="hh-venue">ACL 2025 · Findings</span><h3>Enhancing Multimodal Unified Representations for Cross Modal Generalization</h3><p class="hh-paper-authors"><strong>Hai Huang*</strong>, Yan Xia*, Shengpeng Ji, Shulei Wang, Hanting Wang, Minghui Fang, Jieming Zhu, Zhenhua Dong, Sashuai Zhou, Zhou Zhao</p><div class="hh-paper-links"><a href="https://github.com/haihuangcode/CMG/tree/master/ACL25-FCID%26TOC" target="_blank" rel="noopener noreferrer">Project</a></div></div>
    </article>

    <article class="hh-paper">
      <div class="hh-paper-figure"><img src="{{ '/images/icassp2025_framework.jpg' | relative_url }}" alt="Semantic residual method for multimodal unified discrete representations" width="640" height="400" loading="lazy" decoding="async"></div>
      <div><span class="hh-venue">ICASSP 2025</span><h3><a href="https://arxiv.org/pdf/2412.19128.pdf" target="_blank" rel="noopener noreferrer">Semantic Residual for Multimodal Unified Discrete Representation</a></h3><p class="hh-paper-authors"><strong>Hai Huang</strong>, Shulei Wang, Yan Xia</p><div class="hh-paper-links"><a href="https://arxiv.org/pdf/2412.19128.pdf" target="_blank" rel="noopener noreferrer">Paper</a></div></div>
    </article>

    <article class="hh-paper">
      <div class="hh-paper-figure"><img src="{{ '/images/Overcoming%20both%20Domain%20Shift%20and%20Label%20Shift%20for%20Referring%20Video%20Segmentation.jpg' | relative_url }}" alt="Method for addressing domain and label shifts in referring video segmentation" width="640" height="400" loading="lazy" decoding="async"></div>
      <div><span class="hh-venue">NAACL 2025 · Findings</span><h3><a href="https://aclanthology.org/2025.findings-naacl.167.pdf" target="_blank" rel="noopener noreferrer">Overcoming both Domain Shift and Label Shift for Referring Video Segmentation</a></h3><p class="hh-paper-authors"><strong>Hai Huang</strong>, Sashuai Zhou, Yan Xia</p><div class="hh-paper-links"><a href="https://aclanthology.org/2025.findings-naacl.167.pdf" target="_blank" rel="noopener noreferrer">Paper</a></div></div>
    </article>

    <article class="hh-paper">
      <div class="hh-paper-figure"><img src="{{ '/images/Achieving%20Cross%20Modal%20Generalization%20with%20Multimodal%20Unified%20Representation_overview.png' | relative_url }}" alt="Overview of cross-modal generalization with multimodal unified representations" width="640" height="400" loading="lazy" decoding="async"></div>
      <div><span class="hh-venue">NeurIPS 2023</span><h3><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/c89f09849eb5af489abb122394ff0f0b-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Achieving Cross Modal Generalization with Multimodal Unified Representation</a></h3><p class="hh-paper-authors">Yan Xia*, <strong>Hai Huang*</strong>, Jieming Zhu, Zhou Zhao</p><div class="hh-paper-links"><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/c89f09849eb5af489abb122394ff0f0b-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Paper</a><a href="https://github.com/haihuangcode/CMG" target="_blank" rel="noopener noreferrer">Project</a><span class="show_paper_citations" data="FKvBzQwAAAAJ:u5HHmVD_uO8C"></span></div></div>
    </article>
  </section>

  <section id="honors" aria-labelledby="honors-title">
    <h2 id="honors-title">Honors</h2>
    <ul class="honor-list">
      <li><time datetime="2025-10">2025.10</time><span>National Scholarship</span></li>
      <li><time datetime="2021-10">2021.10</time><span>First Prize, <a href="https://www.robomaster.com" target="_blank" rel="noopener noreferrer">RoboMaster Robotics Competition</a></span></li>
    </ul>
  </section>
  <footer><a href="#about-me" target="_self" data-ss-opts='{"offset":-76,"speed":0}'>Back to top ↑</a></footer>
  <!-- Required by the theme's shared Google Scholar citation loader. -->
  <span id="total_cit" hidden></span>
</div>

<!--
Education (kept from the original page; not displayed):
2023.09 - 2026.03, M.S. in Artificial Intelligence, Zhejiang University
2019.09 - 2023.06, B.S. in Computer Science and Technology, Northeastern University, China
Experience: 2025.01 - 2025.07, Huawei, pretraining a 6B-parameter image generation model based on DiT
-->
