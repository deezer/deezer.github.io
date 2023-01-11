---
layout: post
title: "New Frontiers in Graph Learning: Joint Community Detection and Link Prediction"
date: 2022-12-06 10:10:10 +0200
category: Publication
author: gsalhagalvan
readtime: 6
people:
 - gsalhagalvan
 - rhennequin
publication_type: conference
publication_title: "New Frontiers in Graph Learning: Joint Community Detection and Link Prediction"
publication_year: 2022
publication_authors: G. Salha-Galvan, J. F. Lutzeyer, G. Dasoulas, R. Hennequin, M. Vazirgiannis
publication_conference: NeurIPS GLFrontiers
publication_preprint: "https://arxiv.org/pdf/2211.08972.pdf"
publication_code: "https://github.com/GuillaumeSalhaGalvan/modularity_aware_gae"
---


Graph autoencoders (GAE) and variational graph autoencoders (VGAE) emerged as powerful methods for link prediction (LP). Their performances are less impressive on community detection (CD), where they are often outperformed by simpler alternatives such as the Louvain method. It is still unclear to what extent one can improve CD with GAE and VGAE, especially in the absence of node features. It is moreover uncertain whether one could do so while simultaneously preserving good performances on LP in a multi-task setting.

In this workshop paper, summarizing results from our journal publication (Salha-Galvan et al. 2022), we show that jointly addressing these two tasks with high accuracy is possible. For this purpose, we introduce a community-preserving message passing scheme, doping our GAE and VGAE encoders by considering both the initial graph and Louvain-based prior communities when computing embedding spaces. Inspired by modularity-based clustering, we further propose novel training and optimization strategies specifically designed for joint LP and CD. We demonstrate the empirical effectiveness of our approach, referred to as Modularity-Aware GAE and VGAE, on various real-world graphs.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/salhagalvan22neunet/modawaregae.png' | prepend: site.url }}"
        alt="Modularity-Aware GAE"/>
</div>


Disclaimer: this workshop paper, accepted for presentation at the NeurIPS 2022 Workshop on New Frontiers in Graph Learning (GLFrontiers),
summarizes results from our journal article “Modularity-Aware Graph Autoencoders for Joint Community Detection and Link Prediction” accepted for publication in Elsevier’s Neural Networks
journal in 2022. The purpose of our submission to GLFrontiers was to present this work to a live audience.

