---
layout: post
title: "Improved Robustness in AI-Generated Music Detection"
date: 2026-11-09 8:00:00 +0200
category: Publication
author: rhennequin
readtime: 1
domains: 
 - MIR
people:
 - dafchar
 - rhennequin
publication_type: conference
publication_title: "Improved Robustness in AI-Generated Music Detection"
publication_year: 2026
publication_authors: Emile Dugelay, Thomas Barand, Aurélien Laouar, Baptiste Campeas, Darius Afchar, Romain Hennequin
publication_conference: ISMIR 
publication_preprint: "https://ismir2026program.ismir.net/poster_87.html#paper"
---

AI music generators leave predictable spectral artifacts determined by their architecture. Existing detectors exploit these artifacts with near-perfect accuracy on raw generated tracks, but their performance collapses under simple audio manipulations, such as speed modification or pitch shifting. We address this open robustness problem by introducing a frequency-scaling-invariant detection pipeline that aims to prevent this kind of attack by design. Our method maps audio onto a log-frequency axis via a log-STFT remapping. A single learned cross-correlation filter, combined with max-pooling, provides shift invariance at inference time. Training uses a hybrid loss that jointly supervises binary detection and artifact-peak localization, regularizing boundary weights. Because robustness to speed change is built in by design, the detector is also interpretable: it outputs both a binary decision and an estimate of the applied speed-change factor.
