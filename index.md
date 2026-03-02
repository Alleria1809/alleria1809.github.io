---
layout: page
title: "Xiaoyi (Alleria) Gu"
permalink: /
---

<style>
  main article .content {
    font-family: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif !important;
    color: #111 !important;

    font-size: 0.95rem !important;   /* slightly smaller */
    line-height: 1.65 !important;    /* keep readability */
  }

  main article .content p,
  main article .content li {
    font-weight: 400 !important;
  }

  main article .content h1,
  main article .content h2,
  main article .content h3 {
    font-weight: 600 !important;
  }

  main article .content a,
  main article .content a i {
    color: #111 !important;
  }

  main article .content > p:first-of-type {
    margin-bottom: 0.5rem !important;
  }

  main article .content h2 {
    font-size: 1.35rem !important;
  }

  main article .content .pub-section {
    margin-top: 1.5rem;
  }

  main article .content .pub-list {
    display: flex;
    flex-direction: column;
    gap: 1.25rem;
    margin-top: 1rem;
  }

  main article .content .pub-item {
    display: grid;
    grid-template-columns: 220px 1fr;
    gap: 1.1rem;
    align-items: start;
  }

  main article .content .pub-thumb {
    width: 220px;
    aspect-ratio: 16 / 9;
    border: 1px solid rgba(0,0,0,0.08);
    border-radius: 10px;
    overflow: hidden;
    background: #fff;
  }

  main article .content .pub-thumb img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }

  main article .content .pub-title {
    font-weight: 600;
    margin: 0 0 0.25rem 0;
    line-height: 1.3;
  }

  main article .content .pub-authors {
    margin: 0 0 0.55rem 0;
    color: rgba(0,0,0,0.72) !important;
    font-size: 0.95em;
  }

  main article .content .pub-venue {
    margin: 0 0 0.65rem 0;
    color: rgba(0,0,0,0.62) !important;
    font-size: 0.95em;
  }

  main article .content .pub-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }

  main article .content .pub-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.38rem 0.65rem;
    border: 1px solid rgba(0,0,0,0.22);
    border-radius: 8px;
    text-decoration: none !important;
    color: #111 !important;
    font-size: 0.92em;
    font-weight: 500;
  }

  main article .content .pub-btn:hover {
    border-color: rgba(0,0,0,0.35);
    background: rgba(0,0,0,0.03);
  }

  /* Mobile: stack thumbnail above text */
  @media (max-width: 700px) {
    main article .content .pub-item {
      grid-template-columns: 1fr;
    }
    main article .content .pub-thumb {
      width: 100%;
    }
  }
</style>


<p style="font-size: 1;">
  Applied Scientist at <strong>Twitch (Amazon)</strong>
  <span style="margin-left: 15px;">
    <a href="https://www.linkedin.com/in/alleria1809/" target="_blank">
      <i class="fab fa-linkedin fa-lg"></i>
    </a>
    &nbsp;&nbsp;
    <a href="https://github.com/Alleria1809" target="_blank">
      <i class="fab fa-github fa-lg"></i>
    </a>
    &nbsp;&nbsp;
    <a href="/cv/" target="_blank">
      <i class="fas fa-file-alt fa-lg"></i>
    </a>
    &nbsp;&nbsp;
    <a href="https://scholar.google.com/citations?user=eKXmU18AAAAJ&hl=en" target="_blank">
      <i class="fas fa-graduation-cap fa-lg"></i>
    </a>
  </span>
</p>

---

## **About Me**
<!-- Specializing in **Large-Scale Recommendation / Search Systems, Multi-Objective Optimization, and LLM-powered Personalization** -->

I'm an Applied Scienst in Twitch's Community Discovery Team, designing end-to-end ML pipelines and optimizing large-scale live-stream ranking systems serving millions of users. Before entering the industry, I got my Master's degree in Applied Data Science at USC.

I am particularly interested in:
- Multi-objective learning in recommender systems
- Personalization & search systems
- LLM-assisted ranking and retrieval
- RAG systems and agents

---

## **Professional Experience**

### **Twitch (Amazon) — Applied Scientist (Sep 2024 – Present)**
- Lead large-scale multi-objective optimization for live-stream recommendation systems, defining engagement and retention trade-offs in production. 
- Design and scale segment-aware multi-model architectures (MTL, MMoE, curriculum learning) to support diverse user behaviors.
- Build end-to-end ML ranking pipelines, addressing data quality improvements, model training, offline evaluation, and online A/B experimentation.
- Partner cross-functionally with engineering and data science to clarify problem definitions and deliver measurable metric improvements.

### **SylphAI — Machine Learning Engineer (Apr 2024 – Aug 2024)**

- Built RAG and ReAct agent based chatbot search engine
- Contributed to open-source LLM framework ([AdalFlow](https://github.com/SylphAI-Inc/AdalFlow))

---
<!-- 
## **Education**

**University of Southern California**  
M.S. in Applied Data Science (GPA: 3.92/4.0)

**Beijing Foreign Studies University**  
B.M. in Information Management (GPA: 3.97/4.0)  
National Scholarship; First Class Scholarship; Merit Student <br> 
2021 Beijing Outstanding College Graduate -->

---

<!-- ## **Selected Research**

**Video Generation Models: A Survey of Post-Training and Alignment**  
Under Review at TMLR (2026)  
[TechRxiv link here] -->

<div class="pub-section">
  <h2>Selected Research</h2>

  <div class="pub-list">
    <!-- Paper 1 -->
    <div class="pub-item">
      <div class="pub-thumb">
        <!-- Put your thumbnail here (local is best) -->
        <img src="/assets/img/pubs/teaser.png" alt="Survey thumbnail">
      </div>

      <div>
        <div class="pub-title">Video Generation Models: A Survey of Post-Training and Alignment</div>
        <div class="pub-authors">..., Xiaoyi Gu, ...</div>
        <div class="pub-venue">Under review at TMLR (2026)</div>

        <div class="pub-links">
          <a class="pub-btn" href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.177220111.17351887/v1" target="_blank" rel="noopener">
            <i class="fa-solid fa-file-lines"></i> TechRxiv
          </a>
          <a class="pub-btn" href="https://github.com/CyL97/Awesome-Video-Generation-Post-Training/tree/main" target="_blank" rel="noopener">
            <i class="fa-brands fa-github"></i> GitHub
          </a>
        </div>
      </div>
    </div>
  </div>
</div>
---
