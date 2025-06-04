---
layout: post
title: "S-KEY: Self-supervised Learning of Major and Minor Keys from Audio"
date: 2025-04-10 10:00:00 +0200
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
publication_title: "S-KEY: Self-supervised Learning of Major and Minor Keys from Audio"
publication_year: 2025
publication_authors: Yuexuan Kong, Gabriel Meseguer-Brocal, Vincent Lostanlen, Mathieu Lagrange, Romain Hennequin
publication_conference: ICASSP
publication_preprint: "https://arxiv.org/pdf/2501.12907"
publication_code: "https://github.com/deezer/s-key"
---

STONE, the current method in self-supervised learning for tonality estimation in music signals, cannot distinguish relative keys, such as C major versus A minor. In this article, we extend the neural network architecture and learning objective of STONE to perform self-supervised learning of major and minor keys (S-KEY). Our main contribution is an auxiliary pretext task to STONE, formulated using transposition-invariant chroma features as a source of pseudo-labels. S-KEY matches the supervised state of the art in tonality estimation on FMAKv2 and GTZAN datasets while requiring no human annotation and having the same parameter budget as STONE. We build upon this result and expand the training set of S-KEY to a million songs, thus showing the potential of large-scale self-supervised learning in music information retrieval.
