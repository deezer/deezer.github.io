---
layout: post
title: "Many-to-Many Voice Conversion based Feature Disentanglement using Variational Autoencoder"
date: 2021-04-01 10:00:00 +0200
category: Publication
author: vatran
readtime: 5
people:
 - vatran
publication_type: conference
publication_title: "Many-to-Many Voice Conversion based Feature Disentanglement using Variational Autoencoder"
publication_year: 2021
publication_authors: M. Luong, V-A. Tran
publication_conference: INTERSPEECH
publication_preprint: "https://arxiv.org/pdf/2107.06642.pdf"
publication_code: "https://github.com/v-manhlt3/Disentangle-VAE-for-VC"
---

Voice conversion is a challenging task which transforms the voice characteristics of a source speaker to a target speaker without changing linguistic content.
Recently, there have been many works on many-to-many Voice Conversion (VC) based on Variational Autoencoder (VAEs) achieving good results, however, these methods 
lack the ability to disentangle speaker identity and linguistic content to achieve good performance on unseen speaker scenarios.

In this paper, we propose a new method based on feature disentanglement to tackle many to many voice conversion.
The method has the capability to disentangle speaker identity and linguistic content from utterances, it can convert from many source speakers 
to many target speakers with a single autoencoder network. Moreover, it naturally deals with the unseen target speaker scenarios.
We perform both objective and subjective evaluations to show the competitive performance of our proposed method compared with other state-of-the-art models in terms of naturalness and target speaker similarity.

This paper has been accepted for publication in the proceedings of the Interspeech 2021 conference.
