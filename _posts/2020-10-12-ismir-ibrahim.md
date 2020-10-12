---
layout: post
tags:
  - ismir
  - lyrics
  - multilingual
title: Should we consider the users in contextual music auto-tagging models?
date: 2020-10-12 00:00:00 +0200
category: Publication
author: kibrahim
people:
 - kibrahim
 - eepure
publication_type: conference
publication_title: Should we consider the users in contextual music auto-tagging models?
publication_year: 2020
publication_authors: K. Ibrahim, E. Epure, G. Peeters, G. Richard
publication_conference: ISMIR
#publication_preprint: https://program.ismir2020.net/poster_4-06.html
---

Music tags are commonly used to describe and categorize music. Various auto-tagging models and datasets have been proposed for the automatic music annotation with tags. However, the past approaches often neglect the fact that many of these tags largely depend on the user, especially the tags related to the context of music listening. In this paper, we address this problem by proposing a user-aware music auto-tagging system and evaluation protocol. Specifically, we use both the audio content and user information extracted from the user listening history to predict contextual tags for a given user/track pair. We propose a new dataset of music tracks annotated with contextual tags per user.

<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="{{ '/static/images/publis/ibrahim20ismir/model_arch.png' | prepend: site.url }}"
        alt="Architecture of the Audio+User-based model"/>
</div>

We compare our model to the traditional audio-based model and study the influence of user embeddings on the classification quality. Our work shows that explicitly modeling the user listening history into the automatic tagging process could lead to more accurate estimation of contextual tags. 

This work was presented during the 21st ISMIR Conference in October 2020.