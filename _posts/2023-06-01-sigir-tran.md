---
layout: post
title: "Attention Mixtures for Time-Aware Sequential Recommendation"
date: 2023-06-01 10:00:00 +0200
category: Publication
author: vatran
readtime: 5
people:
 - vatran 
 - gsalhagalvan
 - bmassonisguerra
 - rhennequin
publication_type: conference
publication_title: "Attention Mixtures for Time-Aware Sequential Recommendation"
publication_year: 2023
publication_authors: V-A. Tran, G. Salha-Galvan, B. Sguerra, R. Hennequin
publication_conference: SIGIR
publication_preprint: "https://arxiv.org/pdf/2304.08158.pdf"
publication_code: "https://github.com/deezer/sigir23-mojito"
domains: 
 - RECSYS
---

Transformers emerged as powerful methods for sequential recommendation. However, existing architectures often overlook the complex dependencies between user preferences and the temporal context.

In this short paper, we introduce MOJITO, an improved Transformer sequential recommender system that addresses this limitation. MOJITO leverages Gaussian mixtures of attention-based temporal context and item embedding representations for sequential modeling. Such an approach permits to accurately predict which items should be recommended next to users depending on past actions and the temporal context. 

We demonstrate the relevance of our approach, by empirically outperforming existing Transformers for sequential recommendation on several real-world datasets.

<div class="publication-illustration">
    <img
        style="width: 75%;"
        src="{{ '/static/images/publis/tran2023sigir/mojito.png' | prepend: site.url }}"
        alt="Architecture of our proposed MOJITO system for time-aware sequential recommendation."/>
</div>

This paper has been accepted for publication in the proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2023).
