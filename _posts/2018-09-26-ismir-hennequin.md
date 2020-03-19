---
layout: post
title: Audio Based Disambiguation of Music Genre Tags
date: 2018-09-26 15:44:41 +0200
category: Publication
author: rhennequin
readtime: 6
people:
 - rhennequin
 - mmoussallam
 - royo-letelier

publication_type: conference
publication_title: Audio Based Disambiguation of Music Genre Tags
publication_year: 2018
publication_authors: R. Hennequin, J. Royo-Letelier, M. Moussallam
publication_conference: ISMIR
publication_preprint: "https://arxiv.org/pdf/1809.07256.pdf"
publication_code: "https://github.com/deezer/audio_based_disambiguation_of_music_genre_tags"
---

In this paper, we propose to infer music genre embeddings
from audio datasets carrying semantic information about
genres. We show that such embeddings can be used for disambiguating genre tags (identification of different labels for the same genre, tag translation from a tag system to an other, inference of hierarchical taxonomies on these genre 
tags).

<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="{{ '/static/images/publis/hennequin18ismir/meaning_discrepancy_vertical.png' | prepend: site.url }}"
        alt="meaning discrepancy"/>
</div>

These embeddings are built by training a deep convolutional neural network genre classifier with large audio
datasets annotated with a flat tag system. We show empirically that they makes it possible to retrieve the original
taxonomy of a tag system, spot duplicates tags and translate tags from a tag system to another.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/hennequin18ismir/genre_classifier_for_embeddings.png' | prepend: site.url }}"
        alt="Genre classifier for embeddings"/>
</div>

This paper has been published in the proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR 2018).
