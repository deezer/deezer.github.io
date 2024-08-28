---
layout: post
tags:
  - ismir
  - playlists
  - listening context
title: Prediction of User Listening Contexts for Music Playlists
date: 2020-10-12 00:00:00 +0200
category: Publication
author: eepure
people:
 - akhlif
 - eepure
publication_type: conference
publication_title: Prediction of User Listening Contexts for Music Playlists
publication_year: 2020
publication_authors: J. Choi, A. Khlif, E. V. Epure
publication_conference: ISMIR NLP4MusA
publication_preprint: https://drive.google.com/file/d/1ZUhIrm-XxDOPGTUoGbvuRbSx6nq7i-0Y/view
domains: 
 - MIR
---

In this work, we set up a novel task of <i>playlist context prediction</i>. From a large playlist title corpus, we manually curate a subset of multilingual labels referring to user activities (e.g. <i>"jogging"</i>, <i>"meditation"</i>, <i>"au calme"</i>), which we further consider in the prediction task. 

We explore different approaches to calculate and aggregate track-level contextual semantic embeddings in order to represent a playlist and
predict the playlist context from this representation. Our baseline results show that the task can be addressed with a simple framework using 
information from either audio or distributional similarity of tracks in terms of track-context co-occurrences.

<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="{{ '/static/images/publis/choi20ismir/model.png' | prepend: site.url }}"
        alt=" Diagram of audio embedding model"/>
</div>

This work has been presented at the <i>First Workshop on NLP for Music and Audio</i> (<a href="https://sites.google.com/view/nlp4musa/schedule?authuser=0">NLP4MusA</a>), co-located with <a href="https://www.ismir2020.net/">ISMIR 2020</a>.
It is an extended version of Jeong Choi’s research internship at Deezer in 2019.
