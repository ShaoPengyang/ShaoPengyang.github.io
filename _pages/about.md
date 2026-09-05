---
permalink: /
title: "Shao Pengyang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="home-hero">
  <div class="eyebrow"><span class="status-dot"></span> Postdoctoral Researcher · National University of Singapore</div>
  <h1>Building AI systems we can<br><span>understand, trust, and use.</span></h1>
  <p class="hero-lead">I am <strong>Shao Pengyang (邵鹏阳)</strong>. My research sits at the intersection of <strong>AI + X</strong> and <strong>trustworthy AI</strong>, with a focus on reliable, safe, and responsible learning systems for real-world applications.</p>
  <div class="hero-actions">
    <a class="action action--primary" href="#publications">Explore research <span aria-hidden="true">↘</span></a>
    <a class="action action--secondary" href="/files/CV-spy.pdf">Download CV <span aria-hidden="true">↓</span></a>
  </div>
  <div class="research-tags" aria-label="Research interests">
    <span>LLM Unlearning</span><span>AI Safety</span><span>Recommender Systems</span><span>AI for Education</span>
  </div>
</div>

<aside class="intern-callout" aria-labelledby="intern-title">
  <div class="intern-icon" aria-hidden="true">✦</div>
  <div>
    <div class="intern-kicker">Open for students</div>
    <h2 id="intern-title">Open for research interns</h2>
    <p>I welcome self-motivated students interested in trustworthy AI, LLM unlearning, AI safety, and AI + X. Please email a short introduction, your CV, and your research interests.</p>
  </div>
  <a class="intern-email" href="mailto:shaopymark@gmail.com">shaopymark@gmail.com <span aria-hidden="true">↗</span></a>
</aside>

<section class="home-section about-grid" id="about">
  <div class="section-heading"><span class="section-index">01</span><h2>About</h2></div>
  <div class="about-copy">
    <p>I am a postdoctoral researcher at the <strong>National University of Singapore</strong>, mentored by Prof. <a href="https://www.comp.nus.edu.sg/cs/people/chuats/">Tat-Seng Chua</a> and <a href="https://mysbupt.github.io/">Yunshan Ma</a>. I received my Ph.D. from <strong>Hefei University of Technology</strong> in July 2025, under the supervision of Prof. <a href="https://sites.google.com/view/meng-wang/home">Meng Wang</a>.</p>
    <p>My central question is simple: how can AI systems remain trustworthy, reliable, safe, and responsible when they are deployed in complex domains? I enjoy turning that question into concrete methods, evaluations, and open-source systems.</p>
  </div>
</section>

<section class="home-section" id="publications">
  <div class="section-heading section-heading--split">
    <div><span class="section-index">02</span><h2>Selected research</h2></div>
    <p>Paper links are provided for every publication; code is linked whenever a public implementation is available.</p>
  </div>

  <article class="featured-paper">
    <div class="paper-visual paper-visual--acl"><img src="/images/acl.png" alt="PALU method overview"></div>
    <div class="paper-content">
      <div class="paper-meta"><span class="venue">ACL 2026 · Oral</span><span class="award">Outstanding Paper Award</span></div>
      <h3>Maximizing Local Entropy Where It Matters: Prefix-Aware Localized LLM Unlearning</h3>
      <p class="authors">Naixin Zhai, <strong>Pengyang Shao*</strong>, Binbin Zheng, Yonghui Yang, Fei Shen, Long Bai, Xun Yang*</p>
      <p>PALU severs the causal generation link by suppressing sensitive prefixes and maximizing uncertainty only in the critical vocabulary subspace.</p>
      <div class="paper-links"><a href="https://aclanthology.org/2026.acl-long.893/">Paper ↗</a><a href="https://github.com/nxZhai/PALU">Code ↗</a></div>
    </div>
  </article>

  <article class="featured-paper">
    <div class="paper-visual paper-visual--www"><img src="/images/www2026.png" alt="BalDRO method overview"></div>
    <div class="paper-content">
      <div class="paper-meta"><span class="venue">The Web Conference 2026 · Oral</span></div>
      <h3>BalDRO: A Distributionally Robust Optimization based Framework for Large Language Model Unlearning</h3>
      <p class="authors"><strong>Pengyang Shao</strong>, Naixin Zhai, Lei Chen, Yonghui Yang, Fengbin Zhu*, Xun Yang*, Meng Wang</p>
      <p>BalDRO formulates unlearning as min–sup optimization, adaptively emphasizing hard-to-forget samples while avoiding over-forgetting.</p>
      <div class="paper-links"><a href="https://dl.acm.org/doi/10.1145/3774904.3792975">Paper ↗</a><a href="https://github.com/nxZhai/BalDRO">Code ↗</a></div>
    </div>
  </article>

  <div class="publication-list">
    <article class="publication-row"><div class="publication-year">2026</div><div class="publication-info"><h3>Privacy Matters: Data Attack to Make User Preferences Unlearnable in Recommendation</h3><p><strong>Pengyang Shao</strong>, Le Wu, Kun Zhang, Lei Chen, Meng Wang · <span>ACM TOIS</span></p></div><div class="publication-actions"><a href="https://dl.acm.org/doi/10.1145/3803545">Paper ↗</a></div></article>
    <article class="publication-row"><div class="publication-year">2026</div><div class="publication-info"><h3>Multi-Agent Debate based Concept Augmentation for Enhanced Cognitive Diagnosis</h3><p><strong>Pengyang Shao</strong>, Lei Chen*, Fei Liu, Yonghui Yang, Xun Yang, Meng Wang* · <span>KDD</span></p></div><div class="publication-actions"><a href="/files/KDD_2026_August.pdf">Paper ↓</a></div></article>
    <article class="publication-row"><div class="publication-year">2026</div><div class="publication-info"><h3>Debate over Mixed-knowledge: A Robust Multi-Agent Framework for Incomplete Knowledge Graph Question Answering</h3><p>Jilong Liu, <strong>Pengyang Shao*</strong>, Wei Qin, Fei Liu, Yonghui Yang, Richang Hong* · <span>AAAI · Oral</span></p></div><div class="publication-actions"><a href="https://arxiv.org/abs/2511.12208">Paper ↗</a><a href="https://github.com/liujilong0116/DoM">Code ↗</a></div></article>
    <article class="publication-row"><div class="publication-year">2025</div><div class="publication-info"><h3>Exploring Heterogeneity and Uncertainty for Graph-based Cognitive Diagnosis Models in Intelligent Education</h3><p><strong>Pengyang Shao†</strong>, Yonghui Yang†, Chen Gao, Lei Chen, Kun Zhang, Chenyi Zhuang, Le Wu, Yong Li, Meng Wang* · <span>KDD</span></p></div><div class="publication-actions"><a href="https://dl.acm.org/doi/10.1145/3690624.3709264">Paper ↗</a></div></article>
    <article class="publication-row"><div class="publication-year">2025</div><div class="publication-info"><h3>Towards Reliable Cross-Domain Recommendation: A Disentangled Global Graph Learning based Framework</h3><p><strong>Pengyang Shao</strong>, Zihan Wang, Junsong Xie, Yonghui Yang, Meng Wang · <span>Frontiers of Computer Science</span></p></div><div class="publication-actions"><a href="https://journal.hep.com.cn/fcs/EN/10.1007/s11704-025-51176-4">Paper ↗</a></div></article>
    <article class="publication-row"><div class="publication-year">2025</div><div class="publication-info"><h3>Breaking Student-Concept Sparsity Barrier for Cognitive Diagnosis</h3><p><strong>Pengyang Shao</strong>, Kun Zhang*, Chen Gao*, Lei Chen, Miaomiao Cai, Le Wu, Yong Li, Meng Wang · <span>Frontiers of Computer Science</span></p></div><div class="publication-actions"><a href="https://link.springer.com/article/10.1007/s11704-025-40591-2">Paper ↗</a></div></article>
    <article class="publication-row"><div class="publication-year">2024</div><div class="publication-info"><h3>Average User-side Counterfactual Fairness for Collaborative Filtering</h3><p><strong>Pengyang Shao</strong>, Le Wu*, Kun Zhang, Defu Lian, Richang Hong, Yong Li, Meng Wang* · <span>ACM TOIS</span></p></div><div class="publication-actions"><a href="https://dl.acm.org/doi/10.1145/3656639">Paper ↗</a></div></article>
    <article class="publication-row"><div class="publication-year">2022</div><div class="publication-info"><h3>FairCF: Fairness-aware Collaborative Filtering</h3><p><strong>Pengyang Shao</strong>, Le Wu*, Lei Chen, Kun Zhang, Meng Wang* · <span>Science China Information Sciences</span></p></div><div class="publication-actions"><a href="https://link.springer.com/article/10.1007/s11432-020-3404-y">Paper ↗</a></div></article>
  </div>
  <p class="publication-note">* corresponding author · † equal contribution</p>
</section>

<section class="home-section" id="mentoring">
  <div class="section-heading"><span class="section-index">03</span><h2>Mentoring</h2></div>
  <div class="mentoring-grid">
    <div class="mentor-card"><span class="mentor-result">ACL 2026 · Outstanding Paper</span><h3><a href="https://scholar.google.com/citations?hl=en&user=hwR0iLgAAAAJ">Naixin Zhai</a></h3><p>Prefix-aware LLM unlearning and distributionally robust unlearning.</p></div>
    <div class="mentor-card"><span class="mentor-result">AAAI 2026 · Oral</span><h3><a href="https://scholar.google.com/citations?user=KqbILgIAAAAJ&hl=zh-CN">Jilong Liu</a></h3><p>Robust multi-agent reasoning over incomplete knowledge graphs.</p></div>
    <div class="mentor-card"><span class="mentor-result">Ongoing research</span><h3>Chao Chen · Yanzheng Jin · Chuanpeng Lu</h3><p>LLM personalization, safety alignment, unlearning benchmarks, and AI for finance.</p></div>
  </div>
</section>

<section class="home-section details-grid">
  <div><div class="section-heading"><span class="section-index">04</span><h2>Recognition</h2></div><ul class="timeline-list"><li><time>2026</time><span><strong>Outstanding Paper Award</strong><br>ACL 2026</span></li><li><time>2025</time><span><strong>Best Paper Award</strong><br>TIME Workshop at The Web Conference</span></li><li><time>2024</time><span><strong>Young Talent Support Program</strong><br>China Association for Science and Technology</span></li><li><time>2021–24</time><span><strong>First-Class Graduate Scholarship</strong><br>Awarded annually</span></li></ul></div>
  <div><div class="section-heading"><span class="section-index">05</span><h2>Academic service</h2></div><div class="service-block"><span>Journal reviewer</span><p>IEEE TKDE / TBD · ACM ToRS / TOIS / TiiS · Pattern Recognition · npj Health Systems</p></div><div class="service-block"><span>Conference reviewer</span><p>SIGIR · KDD · The Web Conference · AAAI · ACL · EMNLP · CIKM</p></div></div>
</section>

<section class="contact-band" id="contact">
  <div><span class="section-index">06 · Contact</span><h2>Let’s work on AI<br>that deserves trust.</h2></div>
  <div><p>For research collaborations, internship applications, or relevant opportunities, feel free to get in touch.</p><a href="mailto:shaopymark@gmail.com">shaopymark@gmail.com ↗</a><a href="mailto:shaopymark@nus.edu.sg">shaopymark@nus.edu.sg ↗</a></div>
</section>
