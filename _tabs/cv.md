---
layout: page
icon: fas fa-file-alt
order: 2
title: "CV"
permalink: /cv/
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

<!-- ## Xiaoyi (Alleria) Gu's CV -->

## EDUCATION
- **M.S., Applied Data Science** | University of Southern California, Los Angeles, CA, U.S. (_Dec 2023_)					  
- **B.S., Information Management and Information Systems** | Beijing Foreign Studies University, Beijing, China (_Jun 2021_)
    - **Awards**: National Scholarship (top 0.2%), Merit Student, Beijing Outstanding Graduates

## RESEARCH INTERESTS
Recommendation Systems, Search Algorithms, Multi-Objective Optimization, Personalization, Large Language Models

## PROFESSIONAL EXPERIENCE
**Applied Scientist (Recommendation, Search, MTL, LLM) @ Twitch (_Sep 2024 - Present_)**
- Lead large-scale **multi-objective optimization** for Twitch’s **live-stream recommendation systems**, defining trade-offs across engagement and retention metrics in production.
- Architect and drive end-to-end ML ranking pipelines, resolving data quality challenges, deploying deep learning models and aligning offline evaluation with online experimentation.
- Design and scale user-segment-aware multi-model architectures, introducing debiasing strategies and calibrated new-user utility functions.
- Lead model evolution through segment-weighted loss, curriculum learning, and **multi-task learning (MTL)** frameworks such as the Multi-Gate Mixture-of-Experts (MMoE).
- Enhance Twitch’s search experience through **LLM-based query understanding and reformulation**.
- Collaborate cross-functionally with engineering and data science to de-ambiguate problem definitions, plan execution, and mentor new team members.

**Machine Learning Engineer (Generative AI, Search Engineering, RAG) @ SylphAI Inc. (_Apr 2024 - Aug 2024_)**
- Developed a GenAI chatbot search engine **(RAG)** by embedding texts, indexing, creating the retriever system, ranking and generating candidate-specific answers.
- Built, trained and fine-tuned **deep learning** classifiers using PyTorch.
- Created high-quality data labels utilizing **Large Language Models**(Mistral-7B, GPT-4, and Gemini) with few-shot Prompt Engineering and designed an efficient ETL pipeline to manage data on AWS RDS.
- Implemented agent framework from research with function calls and contributed to an open-source **LLM library** [AdalFlow](https://github.com/SylphAI-Inc/AdalFlow).

**Data Scientist Intern @ Adobe Inc. (_May 2023 – Aug 2023_)**
- Spearheaded **cancellation analysis** and identify cancellation patterns, optimizing the user journey.
- Innovated a product **marketing strategy** with an estimated 10% conversion rate improvement and an $8.3M annual recurring revenue (ARR) lift by deep diving on 5+ metrics using 5M+ data to support decision-making.
- Built a **Logistic Regression** and an **XGBoost model** with feature engineering to analyze the important and significant factors that lead to cancellation on 3M data processed by SQL.

