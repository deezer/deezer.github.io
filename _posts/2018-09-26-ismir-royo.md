---
layout: post
title: Disambiguating Music Artists at Scale with Audio Metric Learning
date: 2018-09-26 15:44:41 +0200
category: Publication
author: royo-letelier
readtime: 6
people:
 - rhennequin
 - mmoussallam
 - royo-letelier
 - vatran

publication_type: conference
publication_title: Disambiguating Music Artists at Scale with Audio Metric Learning
publication_year: 2018
publication_authors: J. Royo-Letelier, R. Hennequin, V-A. Tran, M. Moussallam
publication_conference: ISMIR
publication_preprint: "http://ismir2018.ircam.fr/doc/pdfs/211_Paper.pdf"
publication_code: "https://github.com/deezer/Disambiguating-Music-Artists-at-Scale-with-Audio-Metric-Learning"
domains: 
 - MIR
---

In large music catalogs, artist ambiguities such as different artists sharing the same name or one artist with several distinct names are commonplace. Metadata may not always be sufficient to resolve these ambiguities, especially for small artists with few of them.

In this paper we propose to use metric learning in order to leverage audio as source of information to tackle music artists disambiguation. 

We evaluate the use of embeddings learned from audio in artist classification task on a common benchmark dataset, and we address a clustering task in a homonym artists dataset, showing that our system has the ability to discriminate unknown artists and making it usable for disambiguation in large scale catalogs with addition of new artists.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/royo18ismir/tsne_art20.png' | prepend: site.url }}"
        alt="TSNE representation of artist embeddings"/>
</div>

This paper has been published in the proceedings of the 19th International Society for Music Information Retrieval Conference (ISMIR 2018).
