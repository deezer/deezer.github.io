---
layout: post
title: "The words remain the same: cover detection with lyrics transcription"
date: 2021-11-04 10:00:00 +0200
category: Publication
author: avaglio
readtime: 5
people:
 - avaglio
 - rhennequin
 - mmoussallam
publication_type: conference
publication_title: "The words remain the same: cover detection with lyrics transcription"
publication_year: 2021
publication_authors:  A. Vaglio, R. Hennequin, M. Moussallam, G. Richard
publication_conference: ISMIR
publication_preprint: "https://archives.ismir.net/ismir2021/paper/000089.pdf"
---

Cover detection has gained sustained interest in the scientific community and has recently made significant progress both in terms of scalability and accuracy. However, most approaches are based on the estimation of harmonic and melodic features and neglect lyrics information although it is an important invariant across covers. 

In this work, we propose a novel approach leveraging lyrics without requiring access to full texts though the use of lyrics recognition on audio. Our approach relies on the fusion of a singing voice recognition framework and a more classic tonal-based cover detection method. To the best of our knowledge, this is the first time that lyrics estimation from audio has been explicitly used for cover detection.

Furthermore, we exploit efficient string matching and an approximated nearest neighbors search algorithm which lead to a scalable system which is able to operate on very large databases. Extensive experiments on the largest publicly available cover detection dataset demonstrate the validity of using lyrics information for this task.

<div class="publication-illustration">
    <img
        style="width: 70%;"
        src="{{ '/static/images/publis/vaglio21ismir/avaglio_overview_ismir2021.png' | prepend: site.url }}"
        alt="Overview of the fused cover detection system"/>
</div>

This paper has been accepted for publication in the proceedings of the 21rst International Conference of the ISMIR Society (ISMIR 2021)
