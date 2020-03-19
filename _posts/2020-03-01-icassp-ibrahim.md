---
layout: post
title: "Audio-Based Auto-Tagging with Contextual Tags for Music"
date: 2020-03-01 15:44:41 +0200
category: Publication
author: kibrahim
readtime: 6
projects:
 - MIP-Frontiers
people:
 - kibrahim
 - royo-letelier
 - eepure
publication_preprint: https://hal.archives-ouvertes.fr/hal-02481374
publication_type: conference
publication_title: "Audio-Based Auto-Tagging with Contextual Tags for Music"
publication_year: 2020
publication_authors: K. Ibrahim, J. Royo-Letelier, E. V. Epure, G. Peeters, G. Richard
publication_conference: ICASSP
---

Music listening context such as location or activity has been shown to greatly influence the users' musical tastes.
In this work, we study the relationship between user context and audio content in order to enable context-aware music recommendation agnostic to user data.

For that, we propose a semi-automatic procedure to collect track sets which leverages playlist titles as a proxy for context labelling. Using this, we create and release a dataset of approximately 50k tracks labelled with 15 different contexts.

Then, we present benchmark classification results on the created dataset using an audio auto-tagging model. 
As the training and evaluation of these models are impacted by missing negative labels due to incomplete annotations,
we propose a sample-level weighted cross entropy loss to account for the confidence in missing labels and show improved context prediction results.

<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="{{ '/static/images/publis/ibrahim20icassp/track_cooccurences.png' | prepend: site.baseurl }}"
        alt="Track Co-occurrences on contexts"/>
</div>

This paper has been accepted for publication in the proceedings of the 45th IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2020).
