---
layout: post
title: "Improving Quotation Attribution with Fictional Character Embeddings"
date: 2024-11-12 10:00:00 +0200
category: Publication
author: gmichel
readtime: 1
domains: 
 - NLP
people:
 - gmichel
 - eepure
 - rhennequin
publication_type: conference
publication_title: "Improving Quotation Attribution with Fictional Character Embeddings"
publication_year: 2024
publication_authors: Gaspard Michel, Elena V. Epure, Romain Hennequin, Christophe Cerisara
publication_conference: EMNLP
publication_code: "https://github.com/deezer/character_embeddings_qa"
publication_preprint: "https://aclanthology.org/2024.findings-emnlp.744.pdf"
---

Humans naturally attribute utterances of direct speech to their speaker in literary works.When attributing quotes, we process contextual information but also access mental representations of characters that we build and revise throughout the narrative. Recent methods to automatically attribute such utterances have explored simulating human logic with deterministic rules or learning new implicit rules with neural networks when processing contextual information.However, these systems inherently lack character representations, which often leads to errors in more challenging examples of attribution: anaphoric and implicit quotes.In this work, we propose to augment a popular quotation attribution system, BookNLP, with character embeddings that encode global stylistic information of characters derived from an off-the-shelf stylometric model, Universal Authorship Representation (UAR).We create DramaCV, a corpus of English drama plays from the 15th to 20th century that we automatically annotate for Authorship Verification of fictional characters utterances, and release two versions of UAR trained on DramaCV, that are tailored for literary characters analysis.Then, through an extensive evaluation on 28 novels, we show that combining BookNLP’s contextual information with our proposed global character embeddings improves the identification of speakers for anaphoric and implicit quotes, reaching state-of-the-art performance.