---
layout: post
title: "Flow Moods: Recommending Music by Moods on Deezer"
date: 2022-07-01 10:10:10 +0200
category: Publication
author: gsalhagalvan
readtime: 6
people:
 - gsalhagalvan
publication_type: conference
publication_title: "Flow Moods: Recommending Music by Moods on Deezer"
publication_year: 2022
publication_authors: T. Bontempelli, B. Chapus, F. Rigaud, M. Morlon, M. Lorant, G. Salha-Galvan
publication_conference: RecSys
---

The music streaming service Deezer extensively relies on its Flow algorithm, which generates personalized radio-style playlists of songs, to help users discover musical content. Nonetheless, despite promising results over the past years, Flow used to ignore the moods of users when providing recommendations.

In this paper, we present Flow Moods, an improved version of Flow that addresses this limitation. Flow Moods leverages collaborative filtering, audio content analysis, and mood annotations from professional music curators to generate personalized mood-specific playlists at scale.

We detail the motivations, the development, and the deployment of this system on Deezer. Since its release in 2021, Flow Moods has been recommending music by moods to millions~of~users~every~day.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/salhagalvan22neunet/flow.png' | prepend: site.url }}"
        alt="Flow Moods"/>
</div>

This paper has been accepted for publication in the proceedings of the 16th ACM Conference on Recommender Systems (RecSys 2022).
It will be available online soon.
