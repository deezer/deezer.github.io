---
layout: post
tags:
  - ismir
  - genre
title: Leveraging Knowledge Bases and Parallel Annotations for Music Genre Translation
date: 2019-11-04 15:44:41 +0200
category: Publication
author: eepure
readtime: 2
people:
 - eepure
 - akhlif
 - rhennequin

publication_type: conference
publication_title: Leveraging Knowledge Bases and Parallel Annotations for Music Genre Translation
publication_year: 2019
publication_authors: E. V. Epure, A. Khlif, R. Hennequin
publication_conference: ISMIR
publication_code: "https://github.com/deezer/MusicGenreTranslation"
publication_preprint: "https://arxiv.org/pdf/1907.08698.pdf"
---


Prevalent efforts have been put in automatically inferring genres of musical
items. Yet, the propose solutions often rely on simplifications and fail to
address the diversity and subjectivity of music genres. Accounting for these
has, though, many benefits for aligning knowledge sources, integrating data and
enriching musical items with tags.

Here, we choose a new angle for the genre
study by seeking to predict what would be the genres of musical items in a
target tag system, knowing the genres assigned to them within source tag
systems. We call this a translation task and identify three cases:
1. no common annotated corpus between source and target tag systems exists
2. such a large corpus exists
3. only few common annotations exist.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/epure19ismir/GenreGraphFragment.png' | prepend: site.url }}"
        alt="Graph Genre Mapping"/>
</div>

We propose the related solutions: a knowledge-based translation modeled as
taxonomy mapping,  a statistical translation modeled with maximum likelihood
logistic regression; a hybrid translation modeled with maximum a posteriori
logistic regression with priors given by the knowledge-based translation.

During evaluation, the solutions fit well the identified cases and the hybrid
translation is systematically the most effective w.r.t.  multilabel
classification metrics.


<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/epure19ismir/plot_per_tag_new_colors.png' | prepend: site.url }}"
        alt="Performances"/>
</div>

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/epure19ismir/AUC_macro_to_lastfm_with_and_without_reg.png' | prepend: site.url }}"
        alt="Performances"/>
</div>

This work is a first attempt to unify genre tag systems by leveraging both
representation and interpretation diversity. It has been been published in the proceedings of the 20th International Society for Music Information Retrieval Conference (ISMIR 2019).
