---
layout: post
title: "An Experimental Comparison of Multi-View Self-Supervised Methods for Music Tagging"
date: 2024-04-14 10:00:00 +0200
category: Publication
author: gmeseguerbrocal
readtime: 1
domains: 
 - MIR
people:
 - gmeseguerbrocal
 - ddesblancs
 - rhennequin
publication_type: conference
publication_title: "An Experimental Comparison of Multi-View Self-Supervised Methods for Music Tagging"
publication_year: 2024
publication_authors: G. Meseguer-Brocal, D. Desblancs, R. Hennequin
publication_conference: ICASSP
publication_preprint: "https://arxiv.org/pdf/2404.09177"
---

Self-supervised learning has emerged as a powerful way to pre-train generalizable machine learning models on large amounts of unlabeled data. It is particularly compelling in the music domain, where obtaining labeled data is time-consuming, error-prone, and ambiguous. During the self-supervised process, models are trained on pretext tasks, with the primary objective of acquiring robust and informative features that can later be fine-tuned for specific downstream tasks. The choice of the pretext task is critical as it guides the model to shape the feature space with meaningful constraints for information encoding. In the context of music, most works have relied on contrastive learning or masking techniques. In this study, we expand the scope of pretext tasks applied to music by investigating and comparing the performance of new self-supervised methods for music tagging. We open-source a simple ResNet model trained on a diverse catalog of millions of tracks. Our results demonstrate that, although most of these pre-training methods result in similar downstream results, contrastive learning consistently results in better downstream performance compared to other self-supervised pre-training methods. This holds true in a limited-data downstream context.
