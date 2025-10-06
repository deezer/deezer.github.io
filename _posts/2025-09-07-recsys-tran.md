---
layout: post
title: "'Beyond the past': Leveraging Audio and Human Memory for Sequential Music Recommendation"
date: 2025-10-06 16:00:00 +0200
category: Publication
author: vatran
readtime: 5
people:
 - vatran
 - bmassonisguerra
 - gmeseguerbrocal
 - lbriand
 - manuel.moussallam
publication_type: conference
publication_title: "'Beyond the past': Leveraging Audio and Human Memory for Sequential Music Recommendation"
publication_year: 2025
publication_authors: Viet-Anh Tran, Bruno Sguerra, Gabriel Meseguer-Brocal, Lea Briand, Manuel Moussallam
publication_conference: RecSys
publication_preprint: "https://arxiv.org/pdf/2507.17356"
publication_code: "https://github.com/deezer/recsys25-reacta"
domains: 
 - RECSYS
---

On music streaming services, listening sessions are often composed of a balance of familiar and new tracks. Recently, sequential recommender systems have adopted cognitive-informed approaches, such as Adaptive Control of Thought-Rational (ACT-R), to successfully improve the prediction of the most relevant tracks for the next user session. However, one limitation of using a model inspired by human memory (or the past), is that it struggles to recommend new tracks that users have not previously listened to. To bridge this gap, here we propose a model that leverages audio information to predict in advance the ACT-R-like activation of new tracks and incorporates them into the recommendation scoring process. We demonstrate the empirical effectiveness of the proposed model using proprietary data, which we publicly release along with the model's source code to foster future research in this field.

<div class="publication-illustration">
    <img
        style="width: 75%;"
        src="{{ '/static/images/publis/tran25recsys/reacta.png' | prepend: site.url }}"
        alt="Architecture of REACTA model (dashed arrows are for inference time)."/>
</div>

This paper has been accepted for publication in the proceedings of the 19th ACM Conference on Recommender Systems (RecSys 2025).
