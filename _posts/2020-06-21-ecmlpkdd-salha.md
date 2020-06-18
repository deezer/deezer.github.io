---
layout: post
title: "Simple and Effective Graph Autoencoders with One-Hop Linear Models"
date: 2020-06-21 10:00:00 +0200
category: Publication
author: gsalha
readtime: 5
people:
 - gsalha
 - rhennequin
publication_type: conference
publication_title: "Simple and Effective Graph Autoencoders with One-Hop Linear Models"
publication_year: 2020
publication_authors: G. Salha, R. Hennequin, M. Vazirgiannis
publication_conference: ECML-PKDD
publication_preprint: "https://arxiv.org/pdf/2001.07614.pdf"
publication_code: "https://github.com/deezer/linear_graph_autoencoders"
---

Graphs have become ubiquitous, due to the proliferation of data representing relationships or
interactions among entities. Extracting relevant information from these entities, called the <i>nodes</i> of the graph, 
is crucial to effectively tackle numerous machine learning tasks, such as link prediction or node clustering.

While traditional approaches mainly focused on hand-engineered features, significant improvements were recently achieved
by methods aiming at directly <i>learning</i> node representations that summarize the graph structure.
In a nutshell, these <i>representation learning</i> methods aim at embedding nodes as vectors in a 
low-dimensional vector space in which nodes with structural proximity in the graph should be close,
e.g. by leveraging random walk strategies, matrix factorization or graph neural networks.

In particular, <i>graph autoencoders</i> (AE) and <i>graph variational autoencoders</i> (VAE) recently emerged as
powerful node embedding methods. Based on encoding-decoding schemes, i.e. on the design of low dimensional vector space
representations of nodes (<i>encoding</i>) from which reconstructing the graph (<i>decoding</i>) should be possible, graph
AE and VAE models have been successfully applied to address several challenging learning tasks, with competitive 
results w.r.t. popular baselines. These tasks include link prediction, node clustering, matrix completion for inference and recommendation and molecular graph generation. Existing models usually rely on graph neural networks (GNN) to encode nodes into embeddings. 
More precisely, most of them implement <i>graph convolutional networks</i> (GCN) encoders with multiple layers, a model originally introduced by Kipf and Welling (ICLR 2017).

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/salha19neurips/linearsummary.png' | prepend: site.url }}"
        alt="Linear graph AE and VAE models"/>
</div>

However, despite the prevalent use of GCN encoders in recent literature, the relevance of this design choice has never been thoroughly studied nor challenged.
The actual benefit of incorporating GCNs in graph AE and VAE w.r.t. significantly simpler encoding strategies remains unclear.
In this paper, we propose to tackle this important aspect, showing that GCN-based graph AE and VAE are often unnecessarily complex for numerous applications.
Our work falls into a family of recent efforts questioning the systematic use of complex deep learning methods without clear comparison to less fancy but simpler baselines.

More precisely, our contribution is threefold:
<ul>
    <li> We introduce and study simpler versions of graph AE and VAE, replacing multi-layer GCN encoders by linear models w.r.t. the direct neighborhood (one-hop) adjacency matrix of the graph, involving a unique weight matrix to tune, fewer operations and no activation function. </li>
    <li> Through an extensive empirical analysis on 17 real-world graphs with various sizes and characteristics, we show that these simplified models consistently reach competitive performances w.r.t. GCN-based graph AE and VAE on link prediction and node clustering tasks. We identify the settings where simple linear encoders appear as an effective alternative to GCNs, and as first relevant baseline to implement before diving into more complex models. We also question the relevance of current benchmark datasets (Cora, Citeseer, Pubmed) commonly used in the literature to evaluate graph AE and VAE. </li>
    <li> We publicly release the code of these experiments, for reproducibility and easier future usages. </li>
</ul>


This paper has been published in the proceedings of the European Conference on Machine Learning 
and Principles and Practice of Knowledge Discovery in
Databases (<a href="https://ecmlpkdd2020.net/">ECML-PKDD 2020</a>). 


Moreover, a <a href="https://arxiv.org/pdf/1910.00942.pdf">preliminary version of this work</a> has also 
been presented at the <a href="https://nips.cc/Conferences/2019">NeurIPS 2019</a> workshop on Graph Representation Learning.
