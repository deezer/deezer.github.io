---
layout: post
title: "Topic Modeling on Podcast Short-Text Metadata"
date: 2022-02-10 10:00:00 +0200
category: Publication
author: mbaranes
readtime: 5
people:
 - mbaranes
 - eepure
publication_type: conference
https://github.com/featurespublication_title: "Topic Modeling on Podcast Short-Text Metadata"
publication_year: 2022
publication_authors:  F. B. Valero, M. Baranes, E. V. Epure
publication_conference: ECIR
publication_preprint: "https://arxiv.org/pdf/2201.04419.pdf"
publication_code: "https://github.com/deezer/podcast-topic-modeling"
---

Podcasts have emerged as a massively consumed online content, notably due to wider accessibility of production means and scaled distribution through large streaming platforms. Categorization systems and information access technologies typically use topics as the primary way to organize or navigate podcast collections.

However, annotating podcasts with topics is still quite problematic because the assigned editorial genres are broad, heterogeneous or misleading, or because of data challenges (e.g. short metadata text, noisy transcripts).

In this paper, we assess the feasibility to discover relevant topics from podcast metadata, titles and descriptions, using topic modeling techniques for short text. We also propose a new strategy to leverage named entities (NEs), often present in podcast metadata, in a Non-negative Matrix Factorization (NMF) topic modeling framework. Our experiments on two existing datasets from Spotify and iTunes and Deezer, a new dataset from an online service providing a catalog of podcasts, show that our proposed document representation, NEiCE, leads to improved topic coherence over the baselines.

We release the code for experimental reproducibility of the results.

<div class="publication-illustration">
    <img
        style="width: 70%;"
        src="{{ '/static/images/publis/eepure22ecir/image.png' | prepend: site.url }}"
        alt="Example of topics discovered"/>
</div>

This paper has been accepted for publication in the proceedings of the 44th European Conference on Information Retrieval (ECIR 2022).
