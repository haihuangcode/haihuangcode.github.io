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
.paper-group { margin: 8px 0 4px; padding-bottom: 4px; border-bottom: 1px solid #e7e7e7; }
.paper-group-header { display: flex; flex-wrap: wrap; align-items: center; gap: 8px 16px; padding: 12px 0 4px; }
.academic-home .paper-group-header h3 { flex: 1; margin: 0; font-size: 15px; }
.academic-home .repo-link { display: inline-flex; align-items: center; gap: 6px; padding: 3px 0; color: #48515a; font-size: 12px; white-space: nowrap; }
.github-icon, .star-icon { display: inline-block; width: 14px; height: 14px; flex: none; fill: currentColor; vertical-align: -2px; }
.repo-link > .github-icon { width: 15px; height: 15px; }
.repo-stars { display: inline-flex; align-items: center; gap: 5px; margin-left: 3px; padding-left: 9px; border-left: 1px solid #ddd; color: #666; font-variant-numeric: tabular-nums; }
.repo-stars .star-icon { width: 11px; height: 11px; color: #777; }
.paper-group .hh-paper { grid-template-columns: 150px minmax(0, 1fr); gap: 20px; padding: 14px 0; }
.academic-home .paper-group h4 { margin: 0 0 5px; font-size: 15px; font-weight: 600; line-height: 1.55; }
.hh-paper-links .github-icon { margin-right: 3px; }
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
  .hh-paper, .paper-group .hh-paper { grid-template-columns: 140px minmax(0, 1fr); gap: 18px; }
}
@media (max-width: 560px) {
  .profile-nav { gap: 18px; margin: 12px 0 20px; }
  .hh-paper, .paper-group .hh-paper { grid-template-columns: 1fr; gap: 12px; padding: 18px 0; }
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
  <!-- GitHub mark reused from the bundled Font Awesome 5 Brands (CC BY 4.0): https://fontawesome.com/license/free -->
  <svg width="0" height="0" style="position:absolute" aria-hidden="true" focusable="false">
    <defs>
      <symbol id="profile-github" viewBox="0 0 496 512"><path transform="translate(0 448) scale(1 -1)" d="M165.9 50.6C165.9 48.6 163.6 47 160.7 47C157.4 46.7 155.1 48.3 155.1 50.6C155.1 52.6 157.4 54.2 160.3 54.2C163.3 54.5000000000001 165.9 52.9 165.9 50.6zM134.8 55.1C134.1 53.1 136.1 50.8 139.1 50.2C141.7 49.2 144.7 50.2 145.3 52.2S144 56.5000000000001 141 57.4C138.4 58.1 135.5 57.1 134.8 55.1zM179 56.8C176.1 56.1 174.1 54.2 174.4 51.9C174.7 49.9 177.3 48.6 180.3 49.3C183.2 50 185.2 51.9 184.9 53.9C184.6 55.8 181.9 57.1 179 56.8zM244.8 440C106.1 440 0 334.7 0 196C0 85.1 69.8 -9.8 169.5 -43.2C182.3 -45.5 186.8 -37.6 186.8 -31.1C186.8 -24.9 186.5 9.3 186.5 30.3C186.5 30.3 116.5 15.3 101.8 60.1C101.8 60.1 90.4 89.2000000000001 74 96.7000000000001C74 96.7000000000001 51.1 112.4 75.6 112.1C75.6 112.1 100.5 110.1 114.2 86.3C136.1 47.7 172.8 58.8 187.1 65.4C189.4 81.4 195.9 92.5000000000001 203.1 99.1C147.2 105.3 90.8 113.4 90.8 209.6C90.8 237.1 98.4 250.9000000000001 114.4 268.5C111.8 275 103.3 301.8 117 336.4000000000001C137.9 342.9000000000001 186 309.4000000000001 186 309.4000000000001C206 315 227.5 317.9000000000001 248.8 317.9000000000001S291.6 315 311.6 309.4000000000001C311.6 309.4000000000001 359.7000000000001 343 380.6 336.4000000000001C394.3 301.7000000000001 385.8 275 383.2000000000001 268.5C399.2000000000001 250.8000000000001 409.0000000000001 237.0000000000001 409.0000000000001 209.6C409.0000000000001 113.1 350.1000000000001 105.4 294.2000000000001 99.1C303.4000000000001 91.2000000000001 311.2000000000001 76.2000000000001 311.2000000000001 52.7C311.2000000000001 19.0000000000001 310.9000000000001 -22.6999999999999 310.9000000000001 -30.9C310.9000000000001 -37.4 315.5000000000001 -45.3 328.2000000000001 -43C428.2 -9.8 496 85.1 496 196C496 334.7 383.5 440 244.8 440zM97.2 95.1C95.9 94.1 96.2 91.8 97.9 89.9C99.5 88.3 101.8 87.6 103.1 88.9C104.4 89.9 104.1 92.2000000000001 102.4 94.1C100.8 95.7000000000001 98.5 96.4 97.2 95.1zM86.4 103.2000000000001C85.7 101.9 86.7 100.3000000000001 88.7 99.3000000000001C90.3 98.3000000000001 92.3 98.6000000000001 93 100.0000000000001C93.7 101.3000000000001 92.7 102.9 90.7 103.9C88.7 104.5000000000001 87.1 104.2000000000001 86.4 103.2000000000001zM118.8 67.6C117.2 66.3 117.8 63.3 120.1 61.4C122.4 59.1 125.3 58.8 126.6 60.4C127.9 61.7000000000001 127.3 64.7000000000001 125.3 66.6C123.1 68.9 120.1 69.2000000000001 118.8 67.6zM107.4 82.3C105.8 81.3 105.8 78.7 107.4 76.4C109 74.1 111.7 73.1 113 74.1C114.6 75.4 114.6 78 113 80.3C111.6 82.6 109 83.6 107.4 82.3z"></path></symbol>
      <symbol id="profile-star" viewBox="0 0 24 24"><path d="m12 3 2.78 5.63 6.22.9-4.5 4.39 1.06 6.2L12 17.2l-5.56 2.92 1.06-6.2L3 9.53l6.22-.9Z"></path></symbol>
    </defs>
  </svg>

  <div id="about-me">
    <p class="profile-intro">I am currently with the <strong>Meituan LongCat Team</strong> (<span lang="zh-CN">北斗计划</span>), working on <strong>native multimodal LLM pretraining</strong>. My research focuses on visual representations and ViT pretraining, with interests in 3D, Blender, CAD, and agentic post-training.</p>
    <p class="profile-contact"><a href="mailto:haihuangcode@outlook.com" target="_self">haihuangcode@outlook.com</a><a href="https://github.com/haihuangcode" target="_blank" rel="noopener noreferrer"><svg class="github-icon" viewBox="0 0 496 512" aria-hidden="true" focusable="false"><use href="#profile-github"></use></svg> GitHub</a></p>
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
    <section class="paper-group" aria-labelledby="cmg-title">
      <div class="paper-group-header">
        <h3 id="cmg-title">CMG series</h3>
        <a class="repo-link" href="https://github.com/haihuangcode/CMG" target="_blank" rel="noopener noreferrer" title="haihuangcode/CMG on GitHub">
          <svg class="github-icon" viewBox="0 0 496 512" aria-hidden="true" focusable="false"><use href="#profile-github"></use></svg> GitHub
          <span class="repo-stars"><svg class="star-icon" viewBox="0 0 24 24" role="img" aria-label="Stars"><use href="#profile-star"></use></svg><span data-github-stars="haihuangcode/CMG">239</span></span>
        </a>
      </div>
      <article class="hh-paper">
        <div class="hh-paper-figure"><img src="{{ '/images/OSCMG_framework.jpg' | relative_url }}" alt="Framework for open-set cross-modal generalization" width="640" height="400" loading="lazy" decoding="async"></div>
        <div><span class="hh-venue">ICCV 2025</span><h4>Open-set Cross Modal Generalization via Multimodal Unified Representation</h4><p class="hh-paper-authors"><strong>Hai Huang</strong>, Yan Xia, Shulei Wang, Hanting Wang, Minghui Fang, Shengpeng Ji, Sashuai Zhou, Tao Jin, Zhou Zhao</p><div class="hh-paper-links"><a href="https://github.com/haihuangcode/CMG/tree/master/ICCV25-OSCMG" target="_blank" rel="noopener noreferrer"><svg class="github-icon" viewBox="0 0 496 512" aria-hidden="true" focusable="false"><use href="#profile-github"></use></svg> Code</a></div></div>
      </article>

      <article class="hh-paper">
        <div class="hh-paper-figure"><img src="{{ '/images/ACL2025_TOC.jpg' | relative_url }}" alt="Training-free codebook optimization for multimodal representations" width="640" height="400" loading="lazy" decoding="async"></div>
        <div><span class="hh-venue">ACL 2025 · Findings</span><h4>Enhancing Multimodal Unified Representations for Cross Modal Generalization</h4><p class="hh-paper-authors"><strong>Hai Huang*</strong>, Yan Xia*, Shengpeng Ji, Shulei Wang, Hanting Wang, Minghui Fang, Jieming Zhu, Zhenhua Dong, Sashuai Zhou, Zhou Zhao</p><div class="hh-paper-links"><a href="https://github.com/haihuangcode/CMG/tree/master/ACL25-FCID%26TOC" target="_blank" rel="noopener noreferrer"><svg class="github-icon" viewBox="0 0 496 512" aria-hidden="true" focusable="false"><use href="#profile-github"></use></svg> Code</a></div></div>
      </article>

      <article class="hh-paper">
        <div class="hh-paper-figure"><img src="{{ '/images/Achieving%20Cross%20Modal%20Generalization%20with%20Multimodal%20Unified%20Representation_overview.png' | relative_url }}" alt="Overview of cross-modal generalization with multimodal unified representations" width="640" height="400" loading="lazy" decoding="async"></div>
        <div><span class="hh-venue">NeurIPS 2023</span><h4><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/c89f09849eb5af489abb122394ff0f0b-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Achieving Cross Modal Generalization with Multimodal Unified Representation</a></h4><p class="hh-paper-authors">Yan Xia*, <strong>Hai Huang*</strong>, Jieming Zhu, Zhou Zhao</p><div class="hh-paper-links"><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/c89f09849eb5af489abb122394ff0f0b-Abstract-Conference.html" target="_blank" rel="noopener noreferrer">Paper</a><span class="show_paper_citations" data="FKvBzQwAAAAJ:u5HHmVD_uO8C"></span></div></div>
      </article>
    </section>

    <article class="hh-paper">
      <div class="hh-paper-figure"><img src="{{ '/images/URMMDG_framework.jpg' | relative_url }}" alt="Framework for multimodal domain generalization using unified representations" width="640" height="400" loading="lazy" decoding="async"></div>
      <div><span class="hh-venue">ICCV 2025</span><h3>Bridging Domain Generalization to Multimodal Domain Generalization via Unified Representations</h3><p class="hh-paper-authors"><strong>Hai Huang</strong>, Yan Xia, Sashuai Zhou, Hanting Wang, Shulei Wang, Zhou Zhao</p></div>
    </article>

    <article class="hh-paper">
      <div class="hh-paper-figure"><img src="{{ '/images/icassp2025_framework.jpg' | relative_url }}" alt="Semantic residual method for multimodal unified discrete representations" width="640" height="400" loading="lazy" decoding="async"></div>
      <div><span class="hh-venue">ICASSP 2025</span><h3><a href="https://arxiv.org/pdf/2412.19128.pdf" target="_blank" rel="noopener noreferrer">Semantic Residual for Multimodal Unified Discrete Representation</a></h3><p class="hh-paper-authors"><strong>Hai Huang</strong>, Shulei Wang, Yan Xia</p><div class="hh-paper-links"><a href="https://arxiv.org/pdf/2412.19128.pdf" target="_blank" rel="noopener noreferrer">Paper</a></div></div>
    </article>

    <article class="hh-paper">
      <div class="hh-paper-figure"><img src="{{ '/images/Overcoming%20both%20Domain%20Shift%20and%20Label%20Shift%20for%20Referring%20Video%20Segmentation.jpg' | relative_url }}" alt="Method for addressing domain and label shifts in referring video segmentation" width="640" height="400" loading="lazy" decoding="async"></div>
      <div><span class="hh-venue">NAACL 2025 · Findings</span><h3><a href="https://aclanthology.org/2025.findings-naacl.167.pdf" target="_blank" rel="noopener noreferrer">Overcoming both Domain Shift and Label Shift for Referring Video Segmentation</a></h3><p class="hh-paper-authors"><strong>Hai Huang</strong>, Sashuai Zhou, Yan Xia</p><div class="hh-paper-links"><a href="https://aclanthology.org/2025.findings-naacl.167.pdf" target="_blank" rel="noopener noreferrer">Paper</a></div></div>
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

<script>
(function () {
  if (!window.fetch) return;
  document.querySelectorAll('[data-github-stars]').forEach(function (el) {
    var repo = el.getAttribute('data-github-stars');
    var key = 'github-stars:' + repo;
    function valid(count) { return Number.isSafeInteger(count) && count >= 0; }
    function show(count) { el.textContent = count.toLocaleString('en-US'); }
    try {
      var cached = JSON.parse(localStorage.getItem(key));
      if (cached && valid(cached.count)) {
        show(cached.count);
        var age = Date.now() - cached.time;
        if (age >= 0 && age < 3600000) return;
      }
    } catch (error) { /* Storage can be unavailable in private browsing. */ }
    fetch('https://api.github.com/repos/' + repo, {
      headers: { Accept: 'application/vnd.github+json' }
    }).then(function (response) {
      if (!response.ok) throw new Error('GitHub stars unavailable');
      return response.json();
    }).then(function (data) {
      if (!valid(data.stargazers_count)) return;
      show(data.stargazers_count);
      try {
        localStorage.setItem(key, JSON.stringify({ count: data.stargazers_count, time: Date.now() }));
      } catch (error) { /* The visible count also works without storage. */ }
    }).catch(function () { /* Keep the last known count if GitHub is unavailable. */ });
  });
}());
</script>

<!--
Education (kept from the original page; not displayed):
2023.09 - 2026.03, M.S. in Artificial Intelligence, Zhejiang University
2019.09 - 2023.06, B.S. in Computer Science and Technology, Northeastern University, China
Experience: 2025.01 - 2025.07, Huawei, pretraining a 6B-parameter image generation model based on DiT
-->
