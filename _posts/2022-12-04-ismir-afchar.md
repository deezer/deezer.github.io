---
layout: post
title: "Learning Unsupervised Hierarchies of Audio Concepts"
date: 2022-08-01 10:00:00 +0100
category: Publication
author: dafchar
readtime: 10
people:
 - dafchar
 - rhennequin
publication_type: journal
publication_title: "Learning Unsupervised Hierarchies of Audio Concepts"
publication_year: 2022
publication_authors: D. Afchar, R. Hennequin, V. Guigue
publication_journal: ISMIR 2022
publication_preprint: "https://arxiv.org/pdf/2207.11231"
---

Music signals are difficult to interpret from their low-level features, perhaps even more than images. For instance, highlighting part of a spectrogram or an image is often insufficient to convey high-level ideas that are genuinely relevant to humans. In the following example of a spectrogram...


<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="{{ '/static/images/publis/afchar22ismir/spec_1.png' | prepend: site.url }}"
        alt="Spectrogram"/>
</div>

... let's say that a given model estimated that the track exhibited a "happy" mood. Now, if we were to use a popular explanation technique -- as <a href="https://arxiv.org/abs/1602.04938">LIME</a> -- in order to understand what makes this track "happy", we would obtain something similar to the following <i>attribution map</i>...

<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="{{ '/static/images/publis/afchar22ismir/spec_2.png' | prepend: site.url }}"
        alt="Spectrogram explanation"/>
    <br><span style="color: #AAA; font-size: 0.8em;">
	These two images of a spectrogram and generated explanation were shamefully stolen from <a href="https://arxiv.org/pdf/1905.11760.pdf"><i>"Two-level Explanations in Music Emotion Recognition"</i> V. Praher et al (2019)</a>.</span>
</div>


... which probably made you shrug, since seeing bits of spectrogram does not really enable to understand the decision mechanism involved in estimating that a song is indeed happy.
In some cases, working at the spectrogram level is sufficient: <i>e.g.</i> when predicting the presence of an instrument, we could expect the attribution map to highlight the target instrument melody. The problem at stake is that sometimes, the space in which data is represented -- to be consumed by a model that makes prediction, <b>does not align</b> with the space in which humans would best receive explanation about it.


In the field of computer vision, <b>concept learning</b> was therein proposed to adjust explanations to the right abstraction level (<i>e.g.</i> detect clinical concepts from radiographs). These methods have yet to be used for Music Information Retrieval. In this paper, we adapt concept learning to the realm of music, with its particularities. For instance, music concepts are typically non-independent and of mixed nature (<i>e.g.</i> genre, instruments, mood), unlike previous work that assumed disentangled concepts. We propose a method to learn numerous music concepts from audio and then automatically hierarchise them to expose their mutual relationships. We conduct experiments on datasets of playlists from a music streaming service, serving as a few annotated examples for diverse concepts. Evaluations show that the mined hierarchies are aligned with both ground-truth hierarchies of concepts -- when available -- and with proxy sources of concept similarity in the general case.

<div class="publication-illustration">
    <img
        style="width: 75%;"
        src="{{ '/static/images/publis/afchar22ismir/overview.png' | prepend: site.url }}"
        alt="Overview of the method: 1/ concept computation, 2/ inter-concept similarity, 3/ hierarchy extraction from similarity graph"/>
</div>

Some demo results, are available online to play with: <a href="http://research.deezer.com/concept_hierarchy/">research.deezer.com/concept_hierarchy</a>.