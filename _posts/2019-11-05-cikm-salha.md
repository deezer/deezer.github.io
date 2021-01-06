---
layout: post
title: "Gravity-Inspired Graph Autoencoders for Directed Link Prediction"
date: 2019-11-05 15:44:41 +0200
category: Publication
author: gsalhagalvan
readtime: 6
people:
 - gsalhagalvan
 - rhennequin
 - vatran
publication_type: conference
publication_title: "Gravity-Inspired Graph Autoencoders for Directed Link Prediction"
publication_year: 2019
publication_authors: G. Salha-Galvan, S. Limnios, R. Hennequin, V-A. Tran, M. Vazirgiannis
publication_conference: CIKM
publication_preprint: "https://arxiv.org/pdf/1905.09570.pdf"
publication_code: "https://github.com/deezer/gravity_graph_autoencoders"
---

Graph autoencoders (AE) and variational autoencoders (VAE) recently emerged as powerful node embedding methods. In particular, graph AE and VAE were successfully leveraged to tackle the challenging link prediction problem, aiming at figuring out whether some pairs of nodes from a graph are connected by unobserved edges.

However, these models focus on undirected graphs and therefore ignore the potential direction of the link, which is limiting for numerous real-life applications.

In this paper, we extend the graph AE and VAE frameworks to address link prediction in directed graphs. We present a new gravity-inspired decoder scheme that can effectively reconstruct directed graphs from a node embedding.

We empirically evaluate our method on three different directed link prediction tasks, for which standard graph AE and VAE perform poorly.
We achieve competitive results on three real-world graphs, outperforming several popular baselines. 

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/salha19cikm/graph_visu_cora.png' | prepend: site.url }}"
        alt="Cora directed graph"/>
</div>

This paper has been published in the proceedings of the 28th ACM International Conference on Information and Knowledge Management (CIKM 2019).
