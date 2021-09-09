---
layout: post
title: "A Semi-Personalized System for User Cold Start Recommendation on Music Streaming Apps"
date: 2021-08-15 10:00:00 +0200
category: Publication
author: gsalhagalvan
readtime: 5
people:
 - gsalhagalvan
 - vatran
publication_type: conference
publication_title: "A Semi-Personalized System for User Cold Start Recommendation on Music Streaming Apps"
publication_year: 2021
publication_authors: L. Briand, G. Salha-Galvan, W. Bendada, M. Morlon, V.A. Tran
publication_conference: KDD
publication_preprint: "https://arxiv.org/pdf/2106.03819.pdf"
publication_code: "https://github.com/deezer/semi_perso_user_cold_start"
---

Music streaming services heavily rely on recommender systems to
improve their users’ experience, by helping them navigate through
a large musical catalog and discover new songs, albums or artists.
However, recommending relevant and personalized content to new
users, with few to no interactions with the catalog, is challenging.
This is commonly referred to as the user cold start problem.

In this paper, we present the system recently deployed on the music streaming service Deezer to address this problem. The solution
leverages a semi-personalized recommendation strategy, based on a deep neural network architecture and on a clustering of users
from heterogeneous sources of information. We extensively show the practical impact of this system and its effectiveness at predicting the future musical preferences of cold start users on Deezer,
through both offline and online large-scale experiments.

Besides, we publicly release our code as well as anonymized usage data from our experiments. We hope that this release of industrial resources will benefit future research on user cold start recommendation.

<div class="publication-illustration">
    <img
        style="width: 70%;"
        src="{{ '/static/images/publis/briand21kdd/system.png' | prepend: site.url }}"
        alt="A Semi-Personalized System for User Cold Start Recommendation"/>
</div>

This paper has been accepted for publication in the proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2021).
