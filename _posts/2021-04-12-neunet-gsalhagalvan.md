---
layout: post
title: "FastGAE: Scalable Graph Autoencoders with Stochastic Subgraph Decoding"
date: 2021-04-12 10:10:10 +0200
category: Publication
author: gsalhagalvan
readtime: 6
people:
 - gsalhagalvan
 - rhennequin
 - mmoussallam
publication_type: journal
publication_title: "FastGAE: Scalable Graph Autoencoders with Stochastic Subgraph Decoding"
publication_year: 2021
publication_authors: G. Salha-Galvan, R. Hennequin, J-B. Remy, M. Moussallamm, M. Vazirgiannis
publication_journal: Neural Networks
publication_preprint: "https://arxiv.org/pdf/2002.01910.pdf"
publication_code: "https://github.com/deezer/fastgae"
---

Graph autoencoders (AE) and variational autoencoders (VAE) are powerful node embedding methods, but suffer from scalability issues. In this paper, we introduce _FastGAE_, a general framework to scale graph AE and VAE to large graphs with millions of nodes and edges.

Our strategy, based on an effective stochastic subgraph decoding scheme, significantly speeds up the training of graph AE and VAE while preserving or even improving performances. 

We demonstrate the effectiveness of FastGAE on various real-world graphs, outperforming the few existing approaches to scale graph AE and VAE by a wide margin.

This paper has been accepted for publication in Elsevier's Neural Networks journal (impact factor: 5.53).
