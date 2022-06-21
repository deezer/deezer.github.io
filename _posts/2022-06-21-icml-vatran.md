---
layout: post
title: "Improving Transformers with Probabilistic Attention Keys"
date: 2022-06-21 10:10:10 +0200
category: Publication
author: vatran
readtime: 6
people:
 - vatran
publication_type: conference
publication_title: "Improving Transformers with Probabilistic Attention Keys"
publication_year: 2022
publication_authors: T. Nguyen, T. M. Nguyen, D. D. Le, Du. K. Nguyen, V-A. Tran, R. G. Baraniuk, N. Ho, S. J. Osher 
publication_conference: ICML
publication_preprint: "https://www.researchgate.net/profile/Nhat-Ho-5/publication/355356564_Improving_Transformers_with_Probabilistic_Attention_Keys/links/62a69583a3fe3e3df872f9f7/Improving-Transformers-with-Probabilistic-Attention-Keys.pdf"
---


Multi-head attention is a driving force behind state-of-the-art transformers, which achieve remarkable performance across a variety of natural language processing (NLP) and computer vision tasks. It has been observed that for many applications, those attention heads learn redundant embedding, and most of them can be removed without degrading the performance of the model. Inspired by this observation, we propose

Transformer with a Mixture of Gaussian Keys (Transformer-MGK), a novel transformer architecture that replaces redundant heads in transformers with a mixture of keys at each head. These mixtures of keys follow a Gaussian mixture model and allow each attention head to focus on different parts of the input sequence efficiently. Compared to its conventional transformer counterpart, Transformer-MGK accelerates training and inference, has fewer parameters, and requires fewer FLOPs to compute while achieving comparable or better accuracy across tasks. Transformer-MGK can also be easily extended to use with linear attention. 

We empirically demonstrate the advantage of Transformer-MGK in a range of practical applications, including language modeling and tasks that involve very long sequences. On the Wikitext-103 and Long Range Arena benchmark, Transformer-MGKs with 4 heads attain comparable or better performance to the baseline transformers with 8 heads.

This paper has been accepted for publication at the 39th International Conference on Machine Learning (ICML 2022).
