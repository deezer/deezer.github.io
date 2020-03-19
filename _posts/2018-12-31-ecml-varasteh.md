---
layout: post
title: "Time Warp Invariant Dictionary Learning for Time Series Clustering: Application to Music Data Stream Analysis"
date: 2018-12-31 15:44:41 +0200
category: Publication
author: mmoussallam
readtime: 6
projects:
 - LOCUST
people:
 - mmoussallam

publication_type: conference
publication_title: "Time Warp Invariant Dictionary Learning for Time Series Clustering: Application to Music Data Stream Analysis"
publication_year: 2018
publication_authors: S. Varasteh Yazdi, A. Douzal-Chouakria, P. Gallinari, M. Moussallam
publication_conference: ECML-PKDD
publication_preprint: "https://hal.archives-ouvertes.fr/hal-01898905"
---

This work proposes a time warp invariant sparse coding and dictionary learning framework for time series clustering, where both input samples and atoms define time series of different lengths that involve variable delays. For that, first an l0 sparse coding problem is formalised and a time warp invariant orthogonal matching pursuit based on a new cosine maximisation time warp operator is proposed.

A dictionary learning under time warp is then formalised and a gradient descent solution is developed. Lastly, a time series clustering based on the time warp sparsecoding and dictionary learning is presented. The proposed approach is evaluated and compared to major alternative methods on several public datasets, with an application to Deezer music data stream clustering.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/varasteh18ecml/album_clusters.png' | prepend: site.url }}"
        alt="album_clusters"/>
</div>

This work has been done as part of the ANR LOCUST Grant project of the French National Research Agency.
It has been published in the proceedings of the 2018 European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD 2018).
