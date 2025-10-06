---
layout: post
title: "'Beyond the past': Leveraging Audio and Human Memory for Sequential Music Recommendation"
date: 2025-09-07 10:00:00 +0200
category: Publication
author: vatran
readtime: 4
people:
 - vatran
 - bmassonisguerra
 - gmeseguerbrocal
 - lbriand
 - mmoussallam
publication_type: conference
publication_title: "'Beyond the past': Leveraging Audio and Human Memory for Sequential Music Recommendation"
publication_year: 2025
publication_authors: Viet-Anh Tran,  Bruno Sguerra, Gabriel Messeger-brocal, Lea Briand, Manuel Moussallam
publication_conference: "RecSys"
publication_code: "https://github.com/deezer/recsys25-reacta"
publication_preprint: "https://arxiv.org/pdf/2507.17356"
domains: 
domains: 
 - RECSYS
---

On music streaming services, listening sessions are often composed of a balance of familiar and new tracks. Recently, sequential recommender systems have adopted cognitive-informed approaches, such as Adaptive Control of Thought—Rational (ACT-R), to successfully improve the prediction of the most relevant tracks for the next user session. However, one limitation of using a model inspired by human memory (or the past), is that it struggles to recommend new tracks that users have not previously listened to. To bridge this gap, here we propose a model that leverages audio information to predict in advance the ACT-R-like activation of new tracks and incorporates them into the recommendation scoring process. We demonstrate the empirical effectiveness of the proposed model using proprietary data, which we publicly release along with the model’s source code to foster future research in this field.

<div class="publication-illustration">
    <img
        style="width: 80%;"
        src="{{ '/static/images/publis/tran2025recsys/reacta_architecture.jpg' | prepend: site.url }}"
        alt="Overview of the methodology."/>
</div>



