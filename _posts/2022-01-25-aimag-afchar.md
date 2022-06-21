---
layout: post
title: "Explainability in Music Recommender Systems"
date: 2022-01-25 10:00:00 +0100
category: Publication
author: dafchar
readtime: 20
people:
 - dafchar
 - rhennequin
 - eepure
 - mmoussallam
publication_type: journal
publication_title: "Explainability in Music Recommender Systems"
publication_year: 2022
publication_authors: D. Afchar, A. B. Melchiorre, M. Schedl, R. Hennequin, E. V. Epure, M. Moussallam
publication_journal: AI Magazine
publication_preprint: "https://arxiv.org/pdf/2201.10528"
---

The most common way to listen to recorded music nowadays is via streaming platforms which provide access to tens of millions of tracks.
To assist users in effectively browsing these large catalogs, the integration of Music Recommender Systems (MRSs) has become essential.
Current real-world MRSs are often quite complex and optimized for recommendation accuracy.
They combine several building blocks based on collaborative filtering and content-based recommendation.
This complexity can hinder the ability to explain recommendations to end users, which is particularly important for recommendations perceived as unexpected or inappropriate. While pure recommendation performance often correlates with user satisfaction, explainability has a positive impact on other factors such as trust and forgiveness, which are ultimately essential to maintain user loyalty.


In this article, we discuss how explainability can be addressed in the context of MRSs. 
We provide perspectives on how explainability could improve music recommendation algorithms and enhance user experience. 
First, we review common dimensions and goals of recommenders' explainability and in general of eXplainable Artificial Intelligence (XAI),
and elaborate on the extent to which these apply -- or need to be adapted -- to the specific characteristics of music consumption and recommendation.
Then, we show how explainability components can be integrated within a MRS and in what form explanations can be provided. 
Since the evaluation of explanation quality is decoupled from pure accuracy-based evaluation criteria, we also discuss requirements and strategies for evaluating explanations of music recommendations.
Finally, we describe the current challenges for introducing explainability within a large-scale industrial music recommender system and provide research perspectives.

<div class="publication-illustration">
    <img
        style="width: 75%;"
        src="{{ '/static/images/publis/afchar22aimag/examples.png' | prepend: site.url }}"
        alt="Interpretable Models architecture"/>
</div>
