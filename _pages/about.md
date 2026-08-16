---
permalink: /
title: "Sipeng Shen"
layout: academic-home
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<header class="home-hero" aria-labelledby="home-title">
  <div class="home-hero__content">
    <p class="home-eyebrow">Computer Vision · Privacy · Digital Humans</p>
    <h1 id="home-title">Sipeng Shen</h1>
    <p class="home-hero__role">Master's student at the School of Cyber Science and Engineering, Wuhan University.</p>
    <p class="home-hero__summary">I research privacy protection for 2D digital humans, with a broader interest in face security and generative models.</p>

    <nav class="home-actions" aria-label="Contact and academic profiles">
      <a class="home-button home-button--primary" href="mailto:{{ site.author.email }}">
        <i class="fas fa-envelope" aria-hidden="true"></i><span>Email me</span>
      </a>
      <a class="home-button" href="{{ site.author.googlescholar }}">
        <i class="ai ai-google-scholar" aria-hidden="true"></i><span>Google Scholar</span>
      </a>
      <a class="home-button" href="https://github.com/{{ site.author.github }}">
        <i class="fab fa-github" aria-hidden="true"></i><span>GitHub</span>
      </a>
    </nav>
  </div>

  <figure class="home-hero__portrait">
    <img src="{{ site.author.avatar | prepend: '/images/' | relative_url }}" alt="Portrait of Sipeng Shen">
  </figure>
</header>

<section id="about" class="home-section home-intro" aria-labelledby="about-title">
  <div>
    <p class="home-section__kicker">About</p>
    <h2 id="about-title">Researching safer visual intelligence.</h2>
  </div>
  <div class="home-intro__body">
    <p>I am interested in building visual systems that preserve identity and privacy while remaining robust in real-world conditions.</p>
    <ul class="home-tags" aria-label="Research interests">
      <li>2D Digital Humans</li>
      <li>Privacy Protection</li>
      <li>Face Security</li>
      <li>Generative Models</li>
    </ul>
  </div>
</section>

<section id="education" class="home-section" aria-labelledby="education-title">
  <div class="home-section__heading">
    <div>
      <p class="home-section__kicker">Background</p>
      <h2 id="education-title">Education</h2>
    </div>
    <p>My academic path from Northeastern University to Wuhan University.</p>
  </div>

  <ol class="home-timeline">
    <li>
      <p class="home-timeline__date">2024.09 — 2027.07</p>
      <div>
        <h3>Wuhan University</h3>
        <p>M.S. · School of Cyber Science and Engineering</p>
        <p class="home-meta"><i class="fas fa-location-dot" aria-hidden="true"></i> Wuhan, China</p>
      </div>
    </li>
    <li>
      <p class="home-timeline__date">2020.09 — 2024.07</p>
      <div>
        <h3>Northeastern University</h3>
        <p>B.S.</p>
        <p class="home-meta"><i class="fas fa-location-dot" aria-hidden="true"></i> Shenyang, China</p>
      </div>
    </li>
  </ol>
</section>

<section id="internship" class="home-section" aria-labelledby="internship-title">
  <div class="home-section__heading">
    <div>
      <p class="home-section__kicker">Industry</p>
      <h2 id="internship-title">Internship</h2>
    </div>
    <p>Applied research in efficient and robust digital-human generation.</p>
  </div>

  <article class="experience-card">
    <div class="experience-card__header">
      <div>
        <p class="experience-card__label">AIGC Algorithm Intern</p>
        <h3>Hithink RoyalFlush Cloud Software Co., Ltd.</h3>
      </div>
      <span class="home-status">Lip-sync generation</span>
    </div>

    <div class="experience-card__grid">
      <div>
        <h4>Challenge</h4>
        <p>Reduce the long inference time and high GPU memory consumption of diffusion-based lip-sync models.</p>
      </div>
      <div>
        <h4>Approach</h4>
        <p>Built an end-to-end, two-stage GAN framework for frontal-view lip synchronization, facial reconstruction, and targeted hard-case fine-tuning.</p>
      </div>
      <div>
        <h4>Data &amp; robustness</h4>
        <p>Trained on large video-generation model outputs and real-world datasets, with classifiers identifying profile views, infants, and occlusions.</p>
      </div>
      <div>
        <h4>Result</h4>
        <p>Designed uniform sampling for extreme angles, improving profile-view quality without compromising the model's original performance.</p>
      </div>
    </div>
  </article>
</section>

<section id="publications" class="home-section" aria-labelledby="publications-title">
  <div class="home-section__heading">
    <div>
      <p class="home-section__kicker">Selected work</p>
      <h2 id="publications-title">Publications</h2>
    </div>
    <p>Work on face privacy, adversarial robustness, and visual watermarking.</p>
  </div>

  <ol class="publication-list">
    <li><article class="publication-card"><div class="publication-card__index" aria-hidden="true">01</div><div>
      <h3>ErasableMask: A Robust and Erasable Privacy Protection Scheme against Black-box Face Recognition Models</h3>
      <p class="publication-card__authors"><strong>Sipeng Shen†</strong>, Yunming Zhang†, Dengpan Ye*, Xiuwen Shi, Long Tang, Haoran Duan, Yueyun Shang, Zhihong Tian</p>
      <p class="publication-card__venue"><em>IEEE Transactions on Multimedia</em> · 2025 <span>Accepted</span></p>
    </div></article></li>
    <li><article class="publication-card"><div class="publication-card__index" aria-hidden="true">02</div><div>
      <h3>Three-in-One: Robust Enhanced Universal Transferable Anti-Facial Retrieval in Online Social Networks</h3>
      <p class="publication-card__authors">Yunna Lv, Long Tang, Dengpan Ye, Jiacheng Deng, Yiheng He, and <strong>Sipeng Shen</strong></p>
      <p class="publication-card__venue"><em>IEEE Transactions on Information Forensics and Security</em> · 2025 <span>Accepted</span></p>
    </div></article></li>
    <li><article class="publication-card"><div class="publication-card__index" aria-hidden="true">03</div><div>
      <h3>StyleMark: A Robust Watermarking Method for Art Style Images Against Black-Box Arbitrary Style Transfer</h3>
      <p class="publication-card__authors">Yunming Zhang, Dengpan Ye, <strong>Sipeng Shen</strong>, Jun Wang, Caiyun Xie</p>
      <p class="publication-card__venue"><em>IEEE Transactions on Information Forensics and Security</em> · 2025 <span>Accepted</span></p>
    </div></article></li>
    <li><article class="publication-card"><div class="publication-card__index" aria-hidden="true">04</div><div>
      <h3>DDIP-Watermark: A Double Identity Protection Method Based on Robust Adversarial Watermark</h3>
      <p class="publication-card__authors">Yunming Zhang, Dengpan Ye, Caiyun Xie, <strong>Sipeng Shen</strong>, Z Liu, J Deng, Y Shang, Z Tian</p>
      <p class="publication-card__venue"><em>IEEE Transactions on Dependable and Secure Computing</em> · 2026 <span>Accepted</span></p>
    </div></article></li>
    <li><article class="publication-card"><div class="publication-card__index" aria-hidden="true">05</div><div>
      <h3>Universal Transferable Dual Attack on Anti-Spoofing and Recognition in Facial Security Systems</h3>
      <p class="publication-card__authors">Sirun Chen, Long Tang, <strong>Sipeng Shen</strong>, Ziyi Liu, Yueyun Shang, Dengpan Ye</p>
      <p class="publication-card__venue"><em>International Conference on Intelligent Computing</em> · 2026 <span>Accepted</span></p>
    </div></article></li>
  </ol>
</section>

<div class="home-secondary-grid">
  <section id="honors" class="home-section home-section--compact" aria-labelledby="honors-title">
    <p class="home-section__kicker">Recognition</p>
    <h2 id="honors-title">Honors &amp; Awards</h2>
    <ul class="home-list">
      <li><i class="fas fa-award" aria-hidden="true"></i><span>National Scholarship</span></li>
      <li><i class="fas fa-award" aria-hidden="true"></i><span>First-Class Scholarship, Northeastern University</span></li>
      <li><i class="fas fa-award" aria-hidden="true"></i><span>Outstanding Student, Northeastern University</span></li>
    </ul>
  </section>

  <section id="service" class="home-section home-section--compact" aria-labelledby="service-title">
    <p class="home-section__kicker">Community</p>
    <h2 id="service-title">Academic Service</h2>
    <ul class="home-list">
      <li><i class="fas fa-check" aria-hidden="true"></i><span>Reviewer for <em>Pattern Recognition</em></span></li>
      <li><i class="fas fa-check" aria-hidden="true"></i><span>Reviewer for <em>IEEE Transactions on Multimedia</em></span></li>
    </ul>
  </section>
</div>
