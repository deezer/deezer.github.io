---
layout: post
title: "Cold Start Similar Artists Ranking with Gravity-Inspired Graph Autoencoders"
date: 2021-09-03 10:00:00 +0200
category: Publication
author: gsalhagalvan
readtime: 5
people:
 - gsalhagalvan
 - rhennequin
 - vatran
publication_type: conference
publication_title: "Cold Start Similar Artists Ranking with Gravity-Inspired Graph Autoencoders"
publication_year: 2021
publication_authors:  G. Salha-Galvan, R. Hennequin, B. Chapus, V-A. Tran, M. Vazirgiannis
publication_conference: RecSys
publication_preprint: "https://arxiv.org/pdf/2108.01053.pdf"
publication_code: "https://github.com/deezer/similar_artists_ranking"
---

On an artist’s profile page, music streaming services frequently recommend a ranked list of "similar artists" that fans also liked.
However, implementing such a feature is challenging for new artists, for which usage data on the service (e.g. streams or likes) is not
yet available.

In this paper, we model this cold start similar artists ranking problem as a link prediction task in a directed and attributed
graph, connecting artists to their top-𝑘 most similar neighbors and incorporating side musical information. Then, we leverage a
graph autoencoder architecture to learn node embedding representations from this graph, and to automatically rank the top-𝑘 most
similar neighbors of new artists using a gravity-inspired mechanism.

We empirically show the flexibility and the effectiveness of our framework, by addressing a real-world cold start similar artists ranking problem on Deezer.
Along with this paper, we also publicly release our source code as well as the industrial graph data from our experiments.

<div class="publication-illustration">
    <img
        style="width: 70%;"
        src="{{ '/static/images/publis/salhagalvan21recsys/image.png' | prepend: site.url }}"
        alt="Similar Artists on Deezer"/>
</div>

This paper has been accepted for publication in the proceedings of the 15th ACM Conference on Recommender Systems (RecSys 2021).
