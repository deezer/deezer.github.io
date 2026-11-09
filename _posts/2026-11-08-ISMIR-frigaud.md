---
layout: post
title: "Detection of AI-Generated Stems Within Hybrid Human-AI Music"
date: 2026-11-08 8:00:00 +0200
category: Publication
author: rhennequin
readtime: 1
domains: 
 - MIR
people:
 - frigaud
 - gmeseguerbrocal
 - bmartin
 - rhennequin
publication_type: conference
publication_title: "Detection of AI-Generated Stems Within Hybrid Human-AI Music"
publication_year: 2026
publication_authors: François Rigaud, Gabriel Meseguer Brocal, Benjamin Martin, Romain Hennequin
publication_conference: ISMIR 
publication_preprint: "https://ismir2026program.ismir.net/poster_327.html"
---

This paper presents, to the best of our knowledge, the first study on detecting human-AI hybrid music tracks created by mixing human-produced and AI-generated stems. Building on recent work showing that AI music detectors can identify decoder-related artifacts in fully generated music, we investigate whether such artifacts remain detectable at the stem level after mixing. Using MUSDB18-HQ database in a two-stem vocal + accompaniment setting, we simulate hybrid mixtures by autoencoding individual stems with a neural codec. We compare two strategies combining AI-generated mix detection and source separation. A naive sequential pipeline, where source separation is followed by detection on separated sources, confirms that artifacts associated with an AI-generated stem are not reliably recovered by generic source separation systems. We therefore propose a parallel architecture in which source separation is only used to estimate source-relative energy within the mixture. We then train simple stem-specific binary classifiers that take as input the generated mix prediction together with the relative energy of the target stem on short audio chunks. Averaging chunk-level predictions yields encouraging track-level results, highlighting the potential of such approaches for detecting AI-generated stems in hybrid music.