---
layout: post
title: "Singing Language Identification using a Deep Phonotactic Approach"
date: 2021-04-12 11:10:10 +0200
category: Publication
author: avaglio
readtime: 6
people:
 - avaglio
 - rhennequin
publication_type: conference
publication_title: "Singing Language Identification using a Deep Phonotactic Approach"
publication_year: 2021
publication_authors:  L. Renault, A. Vaglio, R. Hennequin
publication_conference: ICASSP
publication_preprint:
    "https://arxiv.org/pdf/2105.15014.pdf"
publication_code: "https://github.com/deezer/SingingLanguageIdentification"
---

Extensive works have tackled _Language Identification (LID)_ in the speech domain, however their application to
the singing voice trails and performances on _Singing Language Identification (SLID)_ can be improved leveraging recent progresses made in other singing related tasks. 

This work presents a modernized phonotactic system for SLID on polyphonic music: phoneme recognition is performed with
a _Connectionist Temporal Classification (CTC)-based acoustic model_ trained with multilingual data, before language
classification with a recurrent model based on the phonemes estimation. The full pipeline is trained and evaluated with a
large and publicly available dataset, with unprecedented performances. First results of SLID with out-of-set languages
are also presented.


<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="{{ '/static/images/publis/renault21icassp/icassp21.png' | prepend: site.url }}"
        alt="Overview of the proposed Singing Language Identification (SLID) system"/>
</div>


This paper was published in the proceedings of the [46th IEEE International
Conference on Acoustics, Speech and Signal Processing (ICASSP 2021)](https://2021.ieeeicassp.org/). 
It results from Lenny Renault's research internship at Deezer in 2020.
