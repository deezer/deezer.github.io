---
layout: post
title: "From Real to Cloned Singer Identification"
date: 2024-11-08 10:00:00 +0200
category: Publication
author: ddesblancs
readtime: 1
domains: 
 - MIR
people:
 - ddesblancs
 - gmeseguerbrocal
 - rhennequin
 - mmoussallam
publication_type: conference
publication_title: "From Real to Cloned Singer Identification"
publication_year: 2024
publication_authors: Dorian Desblancs, Gabriel Meseguer-Brocal, Romain Hennequin, Manuel Moussallam
publication_conference: ISMIR
publication_preprint: "https://arxiv.org/abs/2407.08647"
---

Cloned voices of popular singers sound increasingly realistic and have gained popularity over the past few years. They however pose a threat to the industry due to personality rights concerns. As such, methods to identify the original singer in synthetic voices are needed. In this paper, we investigate how singer identification methods could be used for such a task. We present three embedding models that are trained using a singer-level contrastive learning scheme, where positive pairs consist of segments with vocals from the same singers. These segments can be mixtures for the first model, vocals for the second, and both for the third. We demonstrate that all three models are highly capable of identifying real singers. However, their performance deteriorates when classifying cloned versions of singers in our evaluation set. This is especially true for models that use mixtures as an input. These findings highlight the need to understand the biases that exist within singer identification systems, and how they can influence the identification of voice deepfakes in music.