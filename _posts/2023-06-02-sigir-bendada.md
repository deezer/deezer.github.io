---
layout: post
title: "A Scalable Framework for Automatic Playlist Continuation on Music Streaming Services"
date: 2023-06-02 10:00:00 +0200
category: Publication
author: gsalhagalvan
readtime: 5
people:
 - gsalhagalvan
publication_type: conference
publication_title: "A Scalable Framework for Automatic Playlist Continuation on Music Streaming Services"
publication_year: 2023
publication_authors: W. Bendada, G. Salha-Galvan, T. Bouabça, T. Cazenave
publication_conference: SIGIR
publication_preprint: "https://arxiv.org/pdf/2304.09061.pdf"
publication_code: "https://github.com/deezer/APC-RTA"
---

Music streaming services often aim to recommend songs for users to extend the playlists they have created on these services. However, extending playlists while preserving their musical characteristics and matching user preferences remains a challenging task, commonly referred to as Automatic Playlist Continuation (APC). Besides, while these services often need to select the best songs to recommend in real-time and among large catalogs with millions of candidates, recent research on APC mainly focused on models with few scalability guarantees and evaluated on relatively small datasets. 

In this paper, we introduce a general framework to build scalable yet effective APC models for large-scale applications.
Based on a represent-then-aggregate strategy, it ensures scalability by design while remaining flexible enough to incorporate a wide range of representation learning and sequence modeling techniques, e.g., based on Transformers. 

We demonstrate the relevance of this framework through in-depth experimental validation on Spotify's Million Playlist Dataset (MPD), the largest public dataset for APC. We also describe how, in 2022, we successfully leveraged this framework to improve APC in production on Deezer. We report results from a large-scale online A/B test on this service, emphasizing the practical impact of our approach in such a real-world application.

<div class="publication-illustration">
    <img
        style="width: 75%;"
        src="{{ '/static/images/publis/bendada2023sigir/playlist.png' | prepend: site.url }}"
        alt="Automatic Playlist Continuation (APC) on Deezer"/>
</div>

This paper has been accepted for publication in the proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2023).
