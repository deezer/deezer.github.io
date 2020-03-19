---
layout: post
title: Codec Independent Lossy Audio Compression Detection
date: 2017-04-05 15:44:41 +0200
category: Publication
readtime: 6
author: rhennequin
people:
 - rhennequin
 - royo-letelier
 - mmoussallam

publication_type: conference
publication_title: "Codec Independent Lossy Audio Compression Detection"
publication_year: 2017
publication_authors: R. Hennequin, J. Royo-Letelier, M. Moussallam
publication_conference: ICASSP
publication_preprint: https://arxiv.org/pdf/1907.08698.pdf
---

In this paper, we propose a method for detecting marks of lossy compression encoding, such as MP3 or AAC, from PCM audio. The
method is based on a convolutional neural network (CNN) applied
to audio spectrograms and trained with the output of various lossy
audio codecs and bitrates. Our method shows good performances on
a large database and robustness to codec type and resampling.

The core idea is that lossy compression leaves traces in the spectrogram of processed files, namely holes (areas of the Time-Frequency plane where values are put to zero) band frequency cuts, and clusters.

Using proper training data, most existing lossy compression algorithm are detected by our system with high accuracy.

<div class="publication-illustration">
    <img
        style="width: 60%;"
        src="{{ '/static/images/publis/hennequin17icassp/spectro_artefacts.png' | prepend: site.url }}"
        alt="Performances"/>
</div>

This paper has been published in the proceedings of the 42nd IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2017).
