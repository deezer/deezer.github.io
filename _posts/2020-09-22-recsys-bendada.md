---
layout: post
tags:
  - recsys
  - bandit
  - recommendation
title: Carousel Personalization in Music Streaming Apps with Contextual Bandits
date: 2020-09-22 00:00:00 +0200
category: Publication
author: gsalha
people:
 - gsalhagalvan
publication_type: conference
publication_title: "Carousel Personalization in Music Streaming Apps with Contextual Bandits"
publication_year: 2020
publication_authors: W. Bendada, G. Salha-Galvan, T. Bontempelli
publication_conference: RecSys
publication_preprint: https://arxiv.org/pdf/2009.06546.pdf
publication_code: https://github.com/deezer/carousel_bandits

---

Recommending relevant and personalized content to users is crucial for media services providers, such as news, 
video or music streaming platforms. Indeed, effective recommender systems improve the users' experience and
engagement on the platform, by helping them navigate through massive amounts of content, enjoy their favorite videos 
or songs, and discover new ones that they might like. As a consequence, significant efforts were initiated to transpose 
promising research on these aspects to industrial-level applications.

In particular, many global mobile apps and websites, notably from the music streaming industry, currently 
leverage <i>swipeable carousels</i> to display recommended content on their homepages. These carousels, 
also referred to as <i>sliders</i> or <i>shelves</i>, consist in ranked lists of items or <i>cards</i> (albums, 
artists, playlists...). A few cards are initially displayed to the users, who can click on them or swipe on the 
screen to see some of the additional cards from the carousel.

<div class="publication-illustration">
    <img
        style="width: 40%;"
        src="{{ '/static/images/publis/bendada20recsys/carousel.png' | prepend: site.url }}"
        alt="Carousels on Deezer"/>
</div>

Selecting and ranking the most relevant cards to 
display is a challenging task, as the catalog size is usually significantly larger than the number of available 
slots in a carousel, and as users have different preferences. While being close to slate recommendation 
and to learning to rank settings, carousel personalization also requires dealing with user feedback to adaptively 
improve the recommended content via online learning strategies, and integrating that some cards from the carousel 
might not be seen by users due to the swipeable structure.

In this paper, we model carousel personalization as a <i>multi-armed bandit with multiple plays</i> learning problem. 
Within our proposed framework, we account for important characteristics of real-world swipeable carousels, 
notably by considering that media services providers have access to contextual information on user preferences, 
that they might not know which cards from a carousel are actually seen by users, and that feedback data from 
carousels might not be available in real time. 

Focusing on music streaming applications, we show the effectiveness of our approach by addressing a 
large-scale carousel-based playlist recommendation task on the global mobile app Deezer.

<div class="publication-illustration">
    <img
        style="width: 60%;"
        src="{{ '/static/images/publis/bendada20recsys/general_exp.png' | prepend: site.url }}"
        alt="Cumulative Regrets of Bandits Policies for Playlist Recommendation"/>
</div>
 
Along with this paper, we publicly release large-scale datasets of user preferences for curated playlists on Deezer, and an open-source environment to recreate comparable learning problems.
The code is available on <a href="https://github.com/deezer/carousel_bandits">GitHub</a> and the datasets are available
on <a href="https://zenodo.org/record/4048678#.X4RYk5Mza3J">Zenodo</a>.

<div class="publication-illustration">
    <img
        style="width: 40%;"
        src="{{ '/static/images/publis/bendada20recsys/zenodo.png' | prepend: site.url }}"
        alt="Datasets"/>
</div>

This paper has been published in the proceedings of the 14th ACM Conference on Recommender Systems (RecSys 2020), and has been shortlisted among the <i>"Best Short Paper Candidates"</i>.
