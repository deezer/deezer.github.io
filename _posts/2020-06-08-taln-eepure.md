---
layout: post
title: "Muzeeglot: a Web Interface for Visualizing Multilingual Music Genre Embedding Spaces"
date: 2020-06-08 00:00:00 +0200
category: Publication
author: eepure
readtime: 4
people:
 - eepure
 - gsalhagalvan
 - fvoituret
 - mbaranes
 - rhennequin
permalink: /muzeeglot
publication_type: conference
publication_title: "Muzeeglot : cross-lingual multi-source music item annotation from music genre embeddings"
publication_year: 2020
publication_month: June
publication_authors: E. V. Epure, G. Salha-Galvan,  F. Voituret, M. Baranes, R. Hennequin
publication_conference: JEP-TALN-RECITAL
publication_preprint: https://www.aclweb.org/anthology/2020.jeptalnrecital-demos.5.pdf
publication_code: "https://github.com/deezer/muzeeglot"
---

We present <i>Muzeeglot</i>, a propotype aiming at illustrating how multilingual music genre embedding space representations can be leveraged to generate cross-lingual music genre annotations for <a href="https://wiki.dbpedia.org">DBpedia</a> music entities (artists, albums, tracks...).

<div class="publication-illustration">
    <img
        style="width: 90%;"
        src="{{ '/static/images/publis/epure20taln/epure20taln.png' | prepend: site.url }}"
        alt="Muzeeglot"/>
</div>

<i>Muzeeglot</i> includes a web interface to visualize these multilingual music genres embeddings.

Based on annotations from one or several sources languages, our system automatically predicts the corresponding annotations in a target language. Languages supported: 

<ul>
    <li>French (fr)</li>
    <li>English (en)</li>
    <li>Spanish (es)</li>
    <li>Dutch (nl)</li>
    <li>Czech (cs)</li>
    <li>Japanese (ja)</li>
</ul>

<i>Muzeeglot</i> has been presented as a demonstration at the <a href="https://jep-taln2020.loria.fr">JEP-TALN-RECITAL 2020</a> conference.
