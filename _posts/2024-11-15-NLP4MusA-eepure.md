---
layout: post
title: "Harnessing High-Level Song Descriptors towards Natural Language-Based Music Recommendation"
date: 2024-11-15 10:00:00 +0200
category: Publication
author: eepure
readtime: 1
domains:
 - NLP
people:
 - eepure
 - gmeseguerbrocal
 - dafchar
 - rhennequin
publication_type: conference
publication_title: "Harnessing High-Level Song Descriptors towards Natural Language-Based Music Recommendation"
publication_year: 2024
publication_authors: Elena V. Epure, Gabriel Meseguer Brocal, Darius Afchar, Romain Hennequin
publication_conference: NLP4MusA (ISMIR)
publication_code: "https://github.com/deezer/nlp4musa_melscribe"
publication_preprint: "https://aclanthology.org/2024.nlp4musa-1.4.pdf"
---

Recommender systems relying on Language Models (LMs) have gained popularity in assisting users to navigate large catalogs. LMs often exploit item high-level descriptors, i.e. categories or consumption contexts, from training data or user preferences. This has been proven effective in domains like movies or products. In music though, understanding how effectively LMs utilize song descriptors for natural language-based music recommendation is relatively limited. In this paper, we assess LMs effectiveness in recommending songs based on user natural language requests and items with descriptors like genres, moods, and listening contexts. We formulate the recommendation as a dense retrieval problem and assess LMs as they become increasingly familiar with data pertinent to the task and domain. Our findings reveal improved performance as LMs are fine-tuned for general language similarity, information retrieval, and mapping longer descriptions to shorter, high-level descriptors in music.