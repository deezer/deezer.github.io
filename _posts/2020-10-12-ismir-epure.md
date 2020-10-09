---
layout: post
tags:
  - ismir
  - lyrics
  - multilingual
title: Multilingual Music Genre Embeddings for Effective Cross-Lingual Music Item Annotation
date: 2020-10-12 00:00:00 +0200
category: Publication
author: eepure
people:
 - eepure
 - gsalha
 - rhennequin
publication_type: conference
publication_title: Multilingual Music Genre Embeddings for Effective Cross-Lingual Music Item Annotation
publication_year: 2020
publication_authors: E. V. Epure, G. Salha, R. Hennequin
publication_conference: ISMIR
#publication_preprint: https://program.ismir2020.net/poster_4-06.html
publication_code: https://github.com/deezer/MultilingualMusicGenreEmbedding
---

Annotating music items with music genres is crucial for music recommendation and information retrieval, yet challenging given that music genres are subjective concepts.
Recently, in order to explicitly consider this subjectivity, the annotation of music items was modeled as a translation task:
predict for a music item its music genres within a target vocabulary or taxonomy (tag system) from a set of music genre tags originating from other tag systems. 
However, without a parallel corpus, previous solutions could not handle tag systems in other languages, being limited to the English-language only.
Here, by learning multilingual music genre embeddings, we enable cross-lingual music genre translation without relying on a parallel corpus.
First, we apply compositionality functions on pre-trained word embeddings to represent multi-word tags.
Second, we adapt the tag representations to the music domain by leveraging multilingual music genres graphs with a modified retrofitting algorithm.

<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="{{ '/static/images/publis/epure20ismir/results.png' | prepend: site.url }}"
        alt="variation in genre tags in several languages"/>
</div>

Experiments show that our method: 1) is effective in translating music genres across tag systems in multiple languages (English, French and Spanish);
2) outperforms the previous baseline in an English-language multi-source translation task.

This work was presented during the 21st ISMIR Conference in October 2020.