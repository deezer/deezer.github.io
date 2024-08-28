---
layout: post
title: Music Mood Detection based on Audio and Lyrics with Deep Neural Net
date: 2018-09-26 15:44:41 +0200
category: Publication
author: rhennequin
readtime: 6
people:
 - rdelbouys
 - rhennequin
 - royo-letelier
 - mmoussallam

publication_type: conference
publication_title: Music Mood Detection based on Audio and Lyrics with Deep Neural Net
publication_year: 2018
publication_authors: R. Delbouys, R. Hennequin, F. Piccoli, J. Royo-Letelier, M. Moussallam
publication_conference: ISMIR
publication_preprint: "https://arxiv.org/pdf/1809.07276.pdf"
publication_code: "https://github.com/deezer/deezer_mood_detection_dataset"
domains: 
 - MIR
---

In this paper, we consider the task of multimodal music mood prediction based on the audio signal and the lyrics of a track.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/delbouys18ismir/audio_plus_lyrics.png' | prepend: site.url }}"
        alt="Audio and Lyrics"/>
</div> 
 
We reproduce the implementation of traditional feature engineering based approaches and propose a new model based on deep learning.

We compare the performance of both approaches on a database containing 18,000 tracks with associated valence and arousal values and show that our approach outperforms classical models on the arousal detection task, and that both approaches perform equally on the valence prediction task.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/delbouys18ismir/deep_model_multimodal.png' | prepend: site.url }}"
        alt="Multimodal"/>
</div>

We also compare the a posteriori fusion with fusion of modalities optimized simultaneously with each unimodal model, and observe a significant improvement of valence prediction.
We release [part of our database](https://github.com/deezer/deezer_mood_detection_dataset) for comparison purposes.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/delbouys18ismir/mood_estimation_results.png' | prepend: site.url }}"
        alt="Performances"/>
</div>

This paper has been published in the proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR 2018).
It generated quite a large press coverage, for instance in [Engadget.com](https://www.engadget.com/2018/09/23/deezer-ai-song-mood-detection/) (EN) or [Clubic.com](https://www.clubic.com/telecharger/logiciel-musique-et-streaming/deezer/actualite-845644-sr-deezer-ia-detecter-humeur-piste-musicale.html) (FR).