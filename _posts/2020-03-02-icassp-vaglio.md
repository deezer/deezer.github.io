---
layout: post
title: "Audio-Based Detection of Explicit Content in Music"
date: 2020-03-02 15:44:41 +0200
category: Publication
author: avaglio
readtime: 6
people:
 - avaglio
 - rhennequin
 - mmoussallam
publication_type: conference
publication_title: "Audio-Based Detection of Explicit Content in Music"
publication_year: 2020
publication_authors: A. Vaglio, R. Hennequin, M. Moussallam, G. Richard, F. d'Alche-Buc
publication_conference: ICASSP
publication_preprint: https://ieeexplore.ieee.org/document/9054278
---

We present a novel automatic system for performing explicit content detection directly
on the audio signal.

Our modular approach uses an audio-to-character recognition model, a keyword spotting
model associated with a dictionary of carefully chosen keywords, and a <i>Random Forest
classification</i> model for the final decision. To the best of our knowledge, this is the
first explicit content detection system based on audio only.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/vaglio20icassp/overview_horiz.png' | prepend: site.url }}"
        alt="Overview of the proposed modular approach"/>
</div>

We demonstrate the individual relevance of our modules on a set of sub-tasks and compare our
approach to a lyrics-informed oracle and an end-to-end naive architecture. The results obtained
are encouraging with a F1-score of 67% on a industrial scale explicit content dataset.

This paper has been published in the proceedings of the 45th IEEE International
Conference on Acoustics, Speech and Signal Processing (ICASSP 2020).
