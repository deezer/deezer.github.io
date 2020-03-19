---
layout: post
title: "Keep It Simple: Graph Autoencoders Without Graph Convolutional Networks"
date: 2019-12-13 10:00:00 +0200
category: Publication
author: gsalha
readtime: 5
people:
 - gsalha
 - rhennequin
publication_type: conference
publication_title: "Keep It Simple: Graph Autoencoders Without Graph Convolutional Networks"
publication_year: 2019
publication_authors: G. Salha, R. Hennequin, M. Vazirgiannis
publication_conference: NeurIPS GRL
publication_preprint: "https://arxiv.org/pdf/1910.00942.pdf"
publication_code: "https://github.com/deezer/linear_graph_autoencoders"
---

Graph autoencoders (AE) and variational autoencoders (VAE) recently emerged as powerful node embedding methods, with promising performances on challenging tasks such as link prediction and node clustering. Graph AE, VAE and most of their extensions rely on graph convolutional networks (GCN) encoders to learn vector space representations of nodes. In this paper, we propose to replace the GCN encoder by a significantly simpler linear model w.r.t. the direct neighborhood (one-hop) adjacency matrix of the graph.

For the two aforementioned tasks, we show that this approach consistently reaches competitive performances w.r.t. GCN-based models for numerous real-world graphs, including all benchmark datasets commonly used to evaluate graph AE and VAE. We question the relevance of repeatedly using these datasets to compare complex graph AE and VAE. We also emphasize the effectiveness of the proposed encoding scheme, that appears as a simpler and faster alternative to GCN encoders for many real-world applications.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/salha19neurips/linearsummary.png' | prepend: site.baseurl }}"
        alt="Cora directed graph"/>
</div>

This paper has been presented at the NeurIPS 2019 Workshop on Graph Representation Learning. An extended conference version of this article is also available here: [Simple and Effective Graph Autoencoders with One-Hop Linear Models](https://arxiv.org/pdf/2001.07614.pdf).