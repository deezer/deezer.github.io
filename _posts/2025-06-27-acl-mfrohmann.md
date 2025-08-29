---
layout: post
title: "Double Entendre: Robust Audio-Based AI-Generated Lyrics Detection via Multi-View Fusion"
date: 2025-06-22 18:00:00 +0200
category: Publication
author: eepure
readtime: 1
domains: 
 - MIR
people:
 - eepure
 - gmeseguerbrocal
 - rhennequin
publication_type: conference
publication_title: "Double Entendre: Robust Audio-Based AI-Generated Lyrics Detection via Multi-View Fusion"
publication_year: 2025
publication_authors: Markus Frohmann, Elena V Epure, Gabriel Meseguer-Brocal, Markus Schedl, Romain Hennequin
publication_conference: ACL
publication_code: "https://github.com/deezer/robust-AI-lyrics-detection"
publication_preprint: "https://arxiv.org/abs/2506.15981"
---

The rapid advancement of AI-based music generation tools is revolutionizing the music industry but also posing challenges to artists, copyright holders, and providers alike. This necessitates reliable methods for detecting such AI-generated content. However, existing detectors, relying on either audio or lyrics, face key practical limitations: audio-based detectors fail to generalize to new or unseen generators and are vulnerable to audio perturbations; lyrics-based methods require cleanly formatted and accurate lyrics, unavailable in practice. To overcome these limitations, we propose a novel, practically grounded approach: a multimodal, modular late-fusion pipeline that combines automatically transcribed sung lyrics and speech features capturing lyrics-related information within the audio. By relying on lyrical aspects directly from audio, our method enhances robustness, mitigates susceptibility to low-level artifacts, and enables practical applicability. Experiments show that our method, DE-detect, outperforms existing lyrics-based detectors while also being more robust to audio perturbations. Thus, it offers an effective, robust solution for detecting AI-generated music in real-world scenarios.
