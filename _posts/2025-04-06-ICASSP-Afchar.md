---
layout: post
title: "AI-Generated Music Detection and its Challenges"
date: 2025-04-10 10:00:00 +0200
category: Publication
author: dafchar
readtime: 1
domains: 
 - MIR
people:
 - dafchar
 - gmeseguerbrocal
 - rhennequin
publication_type: conference
publication_title: "AI-Generated Music Detection and its Challenges"
publication_year: 2025
publication_authors: Darius Afchar, Gabriel Meseguer-Brocal, Romain Hennequin
publication_conference: ICASSP
publication_preprint: "https://arxiv.org/pdf/2501.10111"
publication_code: "https://github.com/deezer/deepfake-detector"
---

In the face of a new era of generative models, the detection of artificially generated content has become a matter of utmost importance. In particular, the ability to create credible minute-long synthetic music in a few seconds on user-friendly platforms poses a real threat of fraud on streaming services and unfair competition to human artists. This paper demonstrates the possibility (and surprising ease) of training classifiers on datasets comprising real audio and artificial reconstructions, achieving a convincing accuracy of 99.8%. To our knowledge, this marks the first publication of a AI-music detector, a tool that will help in the regulation of synthetic media. Nevertheless, informed by decades of literature on forgery detection in other fields, we stress that getting a good test score is not the end of the story. We expose and discuss several facets that could be problematic with such a deployed detector: robustness to audio manipulation, generalisation to unseen models. This second part acts as a position for future research steps in the field and a caveat to a flourishing market of artificial content checkers.
