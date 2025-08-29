---
layout: post
title: "Multi-Class-Token Transformer for Multitask Self-supervised Music Information Retrieval"
date: 2025-06-22 18:00:00 +0200
category: Publication
author: ykong
readtime: 1
domains: 
 - MIR
people:
 - ykong
 - rhennequin
 - gmeseguerbrocal
publication_type: conference
publication_title: "Multi-Class-Token Transformer for Multitask Self-supervised Music Information Retrieval"
publication_year: 2025
publication_authors: Yuexuan Kong, Vincent Lostanlen, Romain Hennequin, Mathieu Lagrange, Gabriel Meseguer-Brocal
publication_conference: WASPAA
publication_code: "https://github.com/deezer/mt2"
publication_preprint: "https://arxiv.org/abs/2507.12996"
---

Contrastive learning and equivariant learning are effective methods for self-supervised learning (SSL) for audio content analysis. Yet, their application to music information retrieval (MIR) faces a dilemma: the former is more effective on tagging (e.g., instrument recognition) but less effective on structured prediction (e.g., tonality estimation); The latter can match supervised methods on the specific task it is designed for, but it does not generalize well to other tasks. In this article, we adopt a best-of-both-worlds approach by training a deep neural network on both kinds of pretext tasks at once. The proposed new architecture is a Vision Transformer with 1-D spectrogram patches (ViT-1D), equipped with two class tokens, which are specialized to different self-supervised pretext tasks but optimized through the same model: hence the qualification of self-supervised multi-class-token multitask (MT2). The former class token optimizes cross-power spectral density (CPSD) for equivariant learning over the circle of fifths, while the latter optimizes normalized temperature-scaled cross-entropy (NT-Xent) for contrastive learning. MT2 combines the strengths of both pretext tasks and outperforms consistently both single-class-token ViT-1D models trained with either contrastive or equivariant learning. Averaging the two class tokens further improves performance on several tasks, highlighting the complementary nature of the representations learned by each class token. Furthermore, using the same single-linear-layer probing method on the features of last layer, MT2 outperforms MERT on all tasks except for beat tracking; achieving this with 18x fewer parameters thanks to its multitasking capabilities. Our SSL benchmark demonstrates the versatility of our multi-class-token multitask learning approach for MIR applications.
