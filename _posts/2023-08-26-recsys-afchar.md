---
layout: post
title: "Of Spiky SVDs and Music Recommendation"
date: 2023-08-26 10:00:00 +0200
category: Publication
author: dafchar
readtime: 5
people:
 - dafchar
 - rhennequin
publication_type: conference
publication_title: "Of Spiky SVDs and Music Recommendation"
publication_year: 2023
publication_authors: D. Afchar, R. Hennequin, V. Guigue
publication_conference: RecSys
publication_preprint: "https://arxiv.org/pdf/2307.01212.pdf"
publication_code: "https://github.com/deezer/spiky_svd"
domains: 
 - RECSYS
---

The truncated singular value decomposition is a widely used methodology in music recommendation for direct similar-item retrieval or embedding musical items for downstream tasks.

This paper investigates a curious effect that we show naturally occurring on many recommendation datasets: spiking formations in the embedding space. We first propose a metric to quantify this spiking organization's strength, then mathematically prove its origin tied to underlying communities of items of varying internal popularity.

With this new-found theoretical understanding, we finally open the topic with an industrial use case of estimating how music embeddings' top-k similar items will change over time under the addition of data.

This paper has been accepted for publication in the proceedings of the 17th ACM Conference on Recommender Systems (RecSys 2023).
