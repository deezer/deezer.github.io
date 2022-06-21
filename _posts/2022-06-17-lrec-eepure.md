---
layout: post
title: "Probing Pre-trained Auto-regressive Language Models for Named Entity Typing and Recognition"
date: 2022-06-17 10:00:00 +0200
category: Publication
author: eepure
readtime: 6
people:
 - eepure
 - rhennequin
publication_type: conference
publication_title: "Probing Pre-trained Auto-regressive Language Models for Named Entity Typing and Recognition"
publication_year: 2022
publication_authors: E. V. Epure, R. Hennequin
publication_conference: LREC
publication_preprint: "https://arxiv.org/pdf/2108.11857.pdf"
publication_code: "https://github.com/deezer/net-ner-probing"
---

Multiple works have proposed to probe language models (LMs) for generalization in named entity (NE) typing (NET) and recognition
(NER). However, little has been done in this direction for auto-regressive models despite their popularity and potential to express a
wide variety of NLP tasks in the same unified format. 

We propose a new methodology to probe auto-regressive LMs for NET and NER
generalization, which draws inspiration from human linguistic behavior, by resorting to meta-learning. We study NEs of various types
individually by designing a zero-shot transfer strategy for NET. Then, we probe the model for NER by providing a few examples at inference. We introduce a novel procedure to assess the model’s memorization of NEs and report the memorization’s impact on the results.

Our findings show that: 1) GPT2, a common pre-trained auto-regressive LM, without any fine-tuning for NET or NER, performs the tasks
fairly well; 2) name irregularity when common for a NE type could be an effective exploitable cue; 3) the model seems to rely more on
NE than contextual cues in few-shot NER; 4) NEs with words absent during LM pre-training are very challenging for both NET and NER.

This paper has been accepted for publication in the proceedings of the 2022 International Conference on Language Resources and Evaluation (LREC 2022).
