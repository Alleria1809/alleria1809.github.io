---
layout: page
icon: fas fa-archive
order: 3
title: About
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


🐈: I adopted **Luna**, a female gray&white domestic shorthair in April, 2024.
<br>
<!-- ![Luna](/assets/img/luna.jpg) -->
<img src="/assets/img/luna.jpg" alt="Luna" width="250"/>

🎮: I'm a 10-year faithful fan of DOTA2.
<br>
<!-- ![DOTA2](https://miro.medium.com/v2/resize:fit:4800/format:webp/1*5jntDOf_Lt2lSxMaK0tOAA.jpeg) -->
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*5jntDOf_Lt2lSxMaK0tOAA.jpeg" alt="DOTA2" width="300"/>

**My DOTA2 project: Draft-Based DOTA2 Winning Camp Prediction**
[Article](https://medium.com/@xiaoyigu/data-science-for-dota2-part-1-data-collection-55d7d7cb07c1)
- Predicted the winning camps of the video game DOTA2 with 16K+ matches crawled by Selenium and Scrapy.
- Researched on DOTA2 winning prediction papers and applied **HIN2Vec graph embedding** to transform the hero relationships into features. Conducted feature engineering and built a set of predictors such as XGBoost (F1 Score 0.64).

<!-- 
## PROJECTS
### Los Angeles Restaurant Heath Inspection and Recommendation
[Video](https://www.youtube.com/watch?v=oiM0AO_HvLQ)
- Led a team as the **Project Manager**. Developed a system identifying risky restaurants collaborating closely with stakeholders using **Agile**. Crawled 9K+ restaurants from Yelp, and applied Record Linkage to integrate Yelp records with LA Open Data.
- Established **risk predicting models (SVM/Random Forest/XGBoost)** with 84% accuracy and 0.7 roc_auc, applied clustering models (PCA/KMeans) and topic modeling to find insights from restaurant groups and Yelp reviews.
- Designed a restaurant recommender. Explored a weighted model with Collaborative Filtering and XGBoost and researched Graph embedding for recommendation on the Yelp dataset with 0.977 RMSE. -->

<!-- 
### Job Recommendation System Based on Knowledge Graph
[Video](https://www.youtube.com/watch?v=EczX-wm0GMc)
- Extracted required skills and diplomas from 10K+ job descriptions with spaCy and fine-tuned BERT models (F1 score 0.66/0.88), applied **entity resolution** to establish a knowledge graph connected with Neo4j. Applied TF-IDF to vectorize features and constructed job category classifiers to classify each job into 15 categories.
- **Deployed web application** with Knowledge Graph to facilitate job search. Utilized similarity metrics to recommend jobs and suggest skills for users to improve.
 -->


