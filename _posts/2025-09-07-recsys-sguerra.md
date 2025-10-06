---
layout: post
title: "Biases in LLM-Generated Musical Taste Profiles for Recommendation"
date: 2025-09-07 10:00:00 +0200
category: Publication
author: bmassonisguerra
readtime: 4
people:
 - bmassonisguerra
 - eepure
 - mmoussallam
publication_type: conference
publication_title: "Biases in LLM-Generated Musical Taste Profiles for Recommendation"
publication_year: 2025
publication_authors: Bruno Sguerra, Elena V Epure , Harin Lee, Manuel Moussallam
publication_conference: "RecSys"
publication_code: "https://github.com/deezer/recsys25_llm_biases"
publication_preprint: "https://arxiv.org/pdf/2507.16708"
domains: 
domains: 
 - RECSYS
---

We explore a novel use case for Large Language Models (LLMs) in recommendation: generating natural language user taste profiles from listening histories. Unlike traditional opaque embeddings, these profiles are interpretable, editable, and give users greater transparency and control over their personalization. However, it is unclear whether users actually recognize themselves in these profiles, and whether some users or items are systematically better represented than others. Understanding this is crucial for trust, usability, and fairness in LLM-based recommender systems.

<div class="publication-illustration">
    <img
        style="width: 80%;"
        src="{{ '/static/images/publis/sguerra25recsys/overview_LLM_bias.jpg' | prepend: site.url }}"
        alt="Overview of the methodology."/>
</div>

To study this, we generate profiles using three different LLMs and evaluate them along two dimensions: self-identification, through a user study with 64 participants, and recommendation performance in a downstream task. We analyze how both are affected by user attributes (e.g., age, taste diversity, mainstreamness) and item features (e.g., genre, country of origin). Our results show that profile quality varies across users and items, and that self-identification and recommendation performance are only weakly correlated. These findings highlight both the promise and the limitations of scrutable, LLM-based profiling in personalized systems.

<div class="publication-illustration">
    <img
        style="width: 80%;"
        src="{{ '/static/images/publis/sguerra25recsys/item_coeff_CR.jpg' | prepend: site.url }}"
        alt="Overview of the methodology."/>
</div>

