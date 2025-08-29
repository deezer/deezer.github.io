---
layout: post
title: "Emergent musical properties of a transformer under contrastive self-supervised learning"
date: 2025-06-22 18:00:00 +0200
category: Publication
author: ykong
readtime: 1
domains: 
 - MIR
people:
 - ykong
 - gmeseguerbrocal
 - rhennequin
publication_type: conference
publication_title: "Emergent musical properties of a transformer under contrastive self-supervised learning"
publication_year: 2025
publication_authors: Yuexuan Kong, Gabriel Meseguer-Brocal, Vincent Lostanlen, Mathieu Lagrange, Romain Hennequin
publication_conference: ISMIR
publication_code: "https://github.com/deezer/emergentmusical-properties-transformer"
publication_preprint: "https://arxiv.org/abs/2506.23873"
---

In music information retrieval (MIR), contrastive self-supervised learning for general-purpose representation models is effective for global tasks such as automatic tagging. However, for local tasks such as chord estimation, it is widely assumed that contrastively trained general-purpose self-supervised models are inadequate and that more sophisticated SSL is necessary; e.g., masked modeling. Our paper challenges this assumption by revealing the potential of contrastive SSL paired with a transformer in local MIR tasks. We consider a lightweight vision transformer with one-dimensional patches in the time--frequency domain (ViT-1D) and train it with simple contrastive SSL through normalized temperature-scaled cross-entropy loss (NT-Xent). Although NT-Xent operates only over the class token, we observe that, potentially thanks to weight sharing, informative musical properties emerge in ViT-1D's sequence tokens. On global tasks, the temporal average of class and sequence tokens offers a performance increase compared to the class token alone, showing useful properties in the sequence tokens. On local tasks, sequence tokens perform unexpectedly well, despite not being specifically trained for. Furthermore, high-level musical features such as onsets emerge from layer-wise attention maps and self-similarity matrices show different layers capture different musical dimensions. Our paper does not focus on improving performance but advances the musical interpretation of transformers and sheds light on some overlooked abilities of contrastive SSL paired with transformers for sequence modeling in MIR.
