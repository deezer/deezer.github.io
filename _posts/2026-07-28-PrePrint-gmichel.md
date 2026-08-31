---
layout: post
title: "Fast and Accurate Quotation Attribution in Literary Texts"
date: 2026-08-03 10:00:00 +0200
category: Publication
author: gmichel
readtime: 1
domains: 
 - NLP
people:
 - gmichel
 - eepure
publication_type: conference
publication_title: "Fast and Accurate Quotation Attribution in Literary Texts"
publication_year: 2026
publication_authors: Gaspard Michel, Hugo Attali, Elena V. Epure
publication_conference: Preprint
publication_code: "https://github.com/gasmichel/ModernBookNLP_QA/"
publication_preprint: "https://arxiv.org/pdf/2608.02359"
---

Attributing quotations to their speakers in literary texts remains an open challenge. Standard methods, which independently predict a speaker mention for each quotation, are efficient but still limited in accuracy. In contrast, large language model (LLM) approaches achieve strong performance, but their computational cost limits their use in large-scale literary analysis. We propose an encoder-based efficient formulation that resolves multiple quotation attributions within a shared, large context window. 
Using our new formulation, *joint scoring*, we report state-of-the-art (SOTA) performance on the Project Dialogism Novel Corpus (PDNC), comprising more than 35,000 manually annotated quotations from 22 English novels.
Our best model reaches 94.5\% overall attribution accuracy while processing novels $20\times$ faster than comparable standard methods and more than $1000\times$ faster than LLM-based approaches on an A100 GPU.
An analysis of models' representations suggests that joint scoring improves on challenging attribution examples by preserving long-range anaphora resolution signal, an information that we found already present in pretrained encoders.
To facilitate adoption, we release ModernBookNLP, a modified fork of BookNLP that replaces its quotation attribution model with our best system available at [this link](https://github.com/gasmichel/ModernBookNLP_QA/).