---
layout: post
title: "GraphLit: Learning Text-Enriched Dynamic Character Network Representations for Literary Study"
date: 2026-05-28 10:00:00 +0200
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
publication_title: "GraphLit: Learning Text-Enriched Dynamic Character Network Representations for Literary Study"
publication_year: 2026
publication_authors: Gaspard Michel, Elena V. Epure, Romain Hennequin, Christophe Cerisara, Mirella Lapata
publication_conference: EMNLP 2026
publication_code: "https://github.com/gasmichel/GraphLit"
publication_preprint: "https://arxiv.org/pdf/2605.28643"
---

Methods to represent literary texts as graphs or sequences of graphs mainly focus on representing character interactions, and often overlook another crucial aspect: the textual context in which characters interact.
We introduce Dynamic Heterogeneous Character Networks (DHCNs), which organize long novels into temporally localized heterogeneous graphs that align
characters with their textual contexts.
We extract around 20,000 DHCNs from Project Gutenberg, and propose GraphLit, a self-supervised learning framework that learns rich literary representations through a masked graph autoencoder objective.
Across a wide range of 12 character-related tasks, GraphLit improves over text-only, graph-only and prior hybrid baselines.
Ablations over different kinds of dynamic graph structures and architectural elements show that grounding characters in their context is the main performance driver, while explicitly encoding narrative order and character relationships provide task-dependent improvements.
Finally, we demonstrate the applicability of DHCNs and GraphLit for literary analysis by studying the link between narrative non-linearity and dynamic social features.