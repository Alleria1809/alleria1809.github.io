---
layout: page
icon: fas fa-archive
order: 3
title: Posts
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

<!-- # Medium Posts -->
## [Implementing Text Chunking for LLMs](https://medium.com/gopenai/implementing-text-chunking-for-llms-98b669606f3f)
**TL;DR**

This article focuses on practical text-splitting strategies for Large Language Models (LLMs). It contains:

- Background of Text Chunking
- Chunking Approaches
- tiktoken and Its Considerations


## [Query Spelling Correction Evolution](https://medium.com/@xiaoyigu/query-spelling-correction-overview-dd19cbb4d47a)
**TL;DR**

Ever searched for a product online, only to be met with “no results found” because of a tiny typo? That’s the multi-billion dollar problem of query spelling correction. Spelling errors kill search results. This article reviews how query correction evolved from 🔡 edit distance | noisy channel → 📊 rankers → 🤖 transformers → 🌐 LLMs, and where the field is heading.