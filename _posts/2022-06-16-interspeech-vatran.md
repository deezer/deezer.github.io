---
layout: post
title: "FlowVocoder: A small Footprint Neural Vocoder based Normalizing Flow for Speech Synthesis"
date: 2022-06-16 10:10:10 +0200
category: Publication
author: vatran
readtime: 6
people:
 - vatran
publication_type: conference
publication_title: "FlowVocoder: A small Footprint Neural Vocoder based Normalizing Flow for Speech Synthesis"
publication_year: 2022
publication_authors: M. Luong, V-A. Tran
publication_conference: INTERSPEECH
publication_preprint: "https://arxiv.org/pdf/2109.13675.pdf"
publication_code: "https://v-manhlt3.github.io/FlowVocoder-demo-pages"
---

Recently, autoregressive neural vocoders have provided remarkable performance in generating high-fidelity speech and have
been able to produce synthetic speech in real-time. However, autoregressive neural vocoders such as WaveFlow are capable of modeling waveform signals from mel-spectrogram,
its number of parameters is significant to deploy on edge devices. Though NanoFlow, which has a small number of parameters, is a state-of-the-art autoregressive neural vocoder, the
performance of NanoFlow is marginally lower than WaveFlow.

Therefore, we propose a new type of autoregressive neural
vocoder called FlowVocoder, which has a small memory footprint and is capable of generating high-fidelity audio in realtime. Our proposed model improves the density estimation of
flow blocks by utilizing a mixture of Cumulative Distribution
Functions (CDF) for bipartite transformation. Hence, the proposed model is capable of modeling waveform signals, while its
memory footprint is much smaller than WaveFlow. 

As shown in experiments, FlowVocoder achieves competitive results with
baseline methods in terms of both subjective and objective evaluation, also, it is more suitable for real-time text-to-speech applications.

This paper has been accepted for publication in the proceedings of the INTERSPEECH 2022 conference.
