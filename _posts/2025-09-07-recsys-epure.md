---
layout: post
tags:
  - recsys
  - NL recommendation
  - multimodal
title: "Just Ask for Music (JAM): Multimodal and Personalized Natural Language Music Recommendation"
date: 2025-09-07 16:00:00 +0200
category: Publication
author: eepure
readtime: 5
people:
 - eepure
 - manuel.moussallam
publication_type: conference
publication_title: "Just Ask for Music (JAM): Multimodal and Personalized Natural Language Music Recommendation"
publication_year: 2025
publication_authors: Alessandro B. Melchiorre, Elena V. Epure, Shahed Masoudian, Gustavo Escobedo, Anna Hausberger, Manuel Moussallam, Markus Schedl
publication_conference: RecSys
publication_preprint: "https://dl.acm.org/doi/full/10.1145/3705328.3748020"
publication_code: "https://github.com/hcai-mms/jam"
domains: 
 - RECSYS
---

Natural language interfaces offer a compelling approach for music recommendation, enabling users to express complex preferences conversationally. While Large Language Models (LLMs) show promise in this direction, their scalability in recommender systems is limited by high costs and latency. Retrieval-based approaches using smaller language models mitigate these issues but often rely on single-modal item representations, overlook long-term user preferences, and require full model retraining, posing challenges for real-world deployment. In this paper, we present JAM (Just Ask for Music), a lightweight and intuitive framework for natural language music recommendation. JAM models user–query–item interactions as vector translations in a shared latent space, inspired by knowledge graph embedding methods like TransE. To capture the complexity of music and user intent, JAM aggregates multimodal item features via cross-attention and sparse mixture-of-experts. We also introduce JAMSessions, a new dataset of over 100k user–query–item triples with anonymized user/item embeddings, uniquely combining conversational queries and user long-term preferences. Our results show that JAM provides accurate recommendations, produces intuitive representations suitable for practical use cases, and can be easily integrated with existing music recommendation stacks.

<div class="publication-illustration">
    <img
        style="width: 75%;"
        src="{{ '/static/images/publis/eepure25recsys/JAM_revised.png' | prepend: site.url }}"
        alt=" JAM (Just Ask for Music) framework outline.."/>
</div>

This paper has been accepted for publication in the proceedings of the 19th ACM Conference on Recommender Systems (RecSys 2025).
