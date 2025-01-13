---
layout: post
title: "Text2Playlist: Generating Personalized Playlists
from Text on Deezer"
date: 2025-04-10 10:00:00 +0200
category: Publication
author: mdelcluze
readtime: 5
people:
 - mdelcluze
 - wbendada
 - lbriand
publication_type: conference
publication_title: "Text2Playlist: Generating Personalized Playlists
from Text on Deezer"
publication_year: 2025
publication_authors: M. Delcluze, A. Khoury, C. Vast, V. Arnaudo,
L. Briand, W. Bendada, T. Bouabça
publication_conference: ECIR
publication_preprint: "https://arxiv.org/pdf/2501.05894"
publication_code: "https://github.com/deezer/new-releases-ecir2024"
domains: 
 - RECSYS
---

The streaming service Deezer heavily relies on the search to help users navigate through its extensive music catalog. Nonetheless, it is primarily designed to find specific items and does not lead directly to a smooth listening experience. We present Text2Playlist, a stand-alone
tool that addresses these limitations. Text2Playlist leverages generative AI, music information retrieval and recommendation systems to generate query-specific and personalized playlists, successfully deployed at scale.

In this paper, we present Text2Playlist, illustrated in the Figure below, a personalized playlist creation tool, explicitly dedicated for broad intent queries, distinct from the search feature. It takes advantage of the recent rise of Large-Language Models (LLMs) and gets inspiration from Retrieval-Augmentation Generation (RAG) framework. Text2Playlist has been deployed on Deezer mobile and web applications for a first test phase of 5\% of premium users since July 2024 and 20\% since October 2024. This paper is organized as follows. In Section 2, we further detail our motivations for such a system. In Section 3 we detail how we use together query extraction, various metadata sources, Deezer recommendation system and LLMs to build this solution. In Section 4, we explain how Text2Playlist is deployed on Deezer and present analysis based on the first data gathered. We conclude and discuss areas of improvement in Section 5.

<div class="publication-illustration">
    <img
        style="width: 70%;"
        src="{{ '/static/images/publis/delcluze25ecir/generativeAIproto.png' | prepend: site.url }}"
        alt="Text2Playlist: Generating Personalized Playlists from Text on Deezer"/>
</div>

This paper has been accepted for publication in the proceedings of the 47th European Conference on Information Retrieval (ECIR 2025) at the Industry Day.
