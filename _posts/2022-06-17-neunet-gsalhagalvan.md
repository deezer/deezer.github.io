---
layout: post
title: "Modularity-Aware Graph Autoencoders for Joint Community Detection and Link Prediction"
date: 2022-06-17 10:10:10 +0200
category: Publication
author: gsalhagalvan
readtime: 6
people:
 - gsalhagalvan
 - rhennequin
publication_type: journal
publication_title: "Modularity-Aware Graph Autoencoders for Joint Community Detection and Link Prediction"
publication_year: 2022
publication_authors: G. Salha-Galvan, J. F. Lutzeyer, G. Dasoulas, R. Hennequin, M. Vazirgiannis
publication_journal: Neural Networks
publication_preprint: "https://arxiv.org/pdf/2202.00961.pdf"
publication_code: "https://github.com/deezer/modularity_aware_gae"
---

Graph autoencoders (GAE) and variational graph autoencoders (VGAE) emerged as powerful methods for link prediction. Their performances are less impressive on community detection problems where, according to recent and concurring experimental evaluations, they are often outperformed by simpler alternatives such as the Louvain method. It is currently still unclear to which extent one can improve community detection with GAE and VGAE, especially in the absence of node features. It is moreover uncertain whether one could do so while simultaneously preserving good performances on link prediction. 

In this paper, we show that jointly addressing these two tasks with high accuracy is possible. For this purpose, we introduce and theoretically study a community-preserving message passing scheme, doping our GAE and VGAE encoders by considering both the initial graph structure and modularity-based prior communities when computing embedding spaces. We also propose novel training and optimization strategies, including the introduction of a modularity-inspired regularizer complementing the existing reconstruction losses for joint link prediction and community detection. 
We demonstrate the empirical effectiveness of our approach, referred to as Modularity-Aware GAE and VGAE, through in-depth experimental validation on various real-world graphs.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/salhagalvan22neunet/modawaregae.png' | prepend: site.url }}"
        alt="Modularity-Aware GAE"/>
</div>

This paper has been accepted for publication in Elsevier's [Neural Networks](https://www.journals.elsevier.com/neural-networks) journal (impact factor: 8.05) in 2022.
