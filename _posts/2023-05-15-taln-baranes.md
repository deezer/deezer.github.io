---
layout: post
title: "Pauzee : Pauses Prediction in Text Reading"
date: 2023-05-15 10:00:00 +0200
category: Publication
author: mbaranes
readtime: 5
people:
 - mbaranes 
 - rhennequin
 - eepure
publication_type: conference
publication_title: "Pauzee : Pauses Prediction in Text Reading"
publication_year: 2023
publication_authors: M. Baranes, K. Hayek, R. Hennequin, E. V. Epure
publication_conference: TALN
publication_preprint: "https://coria-taln-2023.sciencesconf.org/459693/document"
publication_code: "https://github.com/deezer/pauzee_taln23"
---

Silent pauses play a crucial role in text-to-speech synthesis, where they help make the text reading
sound more natural. 

In this work, our goal is to predict these silent pauses from texts to improve
automatic reading systems. As this task has not been extensively studied for French, it is necessary to
build training data dedicated to the prediction of pauses.

We propose a strategy for inferring pauses, based on temporal information from transcribed speech, in order to obtain such a corpus. We then
show that with the help of a model based on Transformers and appropriate data, it is possible to obtain promising results for the prediction of pauses produced by a speaker during text reading.

<div class="publication-illustration">
    <img
        style="width: 75%;"
        src="{{ '/static/images/publis/baranes2023taln/pauzee.png' | prepend: site.url }}"
        alt="Pauses prediction with Pauzee."/>
</div>

This paper has been accepted for publication in the proceedings of the TALN 2023 conference.

The full article is in French.
