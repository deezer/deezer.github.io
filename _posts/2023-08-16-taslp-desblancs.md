---
layout: post
title: "Zero-Note Samba: Self-Supervised Beat Tracking"
date: 2023-08-16 18:00:00 +0200
category: Publication
author: ddesblancs
readtime: 6
people:
 - ddesblancs
 - rhennequin
publication_type: journal
publication_title: "Zero-Note Samba: Self-Supervised Beat Tracking"
publication_year: 2023
publication_authors: D. Desblancs, V. Lostanlen, R. Hennequin
publication_journal: IEEE/ACM Transactions on Audio, Speech, and Language Processing
publication_preprint: "https://t.co/yeMBPHw7yA"
publication_code: "https://t.co/pqxFwER86S"
---

Supervised machine learning for music information retrieval requires a large annotated training set, and is thus an expensive and time-consuming process. To circumvent this problem, we propose to train deep neural networks to perceive beats in musical recordings despite having little or no access to human annotations. The key idea is to train two fully convolutional networks in parallel, which we name ``Zero-Note Samba'' (ZeroNS): the first analyzes the percussive part of a musical piece whilst the second analyzes its non-percussive part. These networks learn a self-supervised pretext task of synchrony prediction (sync-pred), which simulates the ability of musicians to groove together when playing in the same band. Sync-pred encourages the two networks to return similar outputs if the underlying musical parts are synchronized, yet dissimilar outputs if the parts are out of sync. In practice, we obtain the instrumental parts from commercial recordings via an off-the-shelf source separation system: Spleeter. 

After self-supervised learning with sync-pred, ZeroNS produces a sparse output that resembles a beat detection function. When used in conjunction with a dynamic Bayesian network, ZeroNS surpasses the state of the art in unsupervised beat tracking. Furthermore, fine-tuning ZeroNS to a small set of labeled data (of the order of one to ten songs) matches the performance of a fully supervised network on 96 songs. Lastly, we show that pre-training a supervised model with sync-pred mitigates dataset bias and thus improves cross-dataset generalization, at no extra annotation cost.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/desblancs23taslp/flowchart.png' | prepend: site.url }}"
        alt="Functional diagram of Zero-Note Samba"/>
</div>

This paper has been published in the IEEE/ACM [Transactions on Audio, Speech, and Language Processing](https://signalprocessingsociety.org/publications-resources/ieeeacm-transactions-audio-speech-and-language-processing) journal in 2023.