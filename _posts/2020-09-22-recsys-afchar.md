---
layout: post
tags:
  - recsys
  - interpretable
  - recommendation
title: Making Neural Networks Interpretable with Attribution
date: 2020-09-22 00:00:00 +0200
category: Publication
author: dafchar
people:
 - dafchar
 - rhennequin
publication_type: conference
publication_title: "Making Neural Networks Interpretable with Attribution: Application to Implicit Signals Prediction"
publication_year: 2020
publication_authors: D. Afchar, R. Hennequin
publication_conference: RecSys
publication_preprint: https://arxiv.org/pdf/2008.11406.pdf
publication_code: https://github.com/deezer/interpretable_nn_attribution
---

Explaining recommendations enables users to understand whether recommended items are relevant to their needs and has been shown to increase their trust in the system. More generally, if designing explainable machine learning models is key to check the sanity and robustness of a decision process and improve their efficiency, it however remains a challenge for complex architectures, especially deep neural networks that are often deemed "black-box". In this paper, we propose a novel formulation of interpretable deep neural networks for the attribution task. Differently to popular post-hoc methods, our approach is interpretable by design. Using masked weights, hidden features can be deeply attributed, split into several input-restricted sub-networks and trained as a boosted mixture of experts. Experimental results on synthetic data and real-world recommendation tasks demonstrate that our method enables to build models achieving close predictive performances to their non-interpretable counterparts, while providing informative attribution interpretations.

<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="{{ '/static/images/publis/afchar20recsys/principle.png' | prepend: site.url }}"
        alt="Interpretable Models architecture"/>
</div>

This paper has been published in the proceedings of the 14th ACM Conference on Recommender Systems (RecSys 2020).
