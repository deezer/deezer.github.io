---
layout: post
title: "Let’s Get It Started: Fostering the Discoverability of New Releases on Deezer"
date: 2024-03-28 10:00:00 +0200
category: Publication
author: lbriand
readtime: 5
people:
 - lbriand
 - gsalhagalvan
publication_type: conference
publication_title: "Let’s Get It Started: Fostering the Discoverability of New Releases on Deezer"
publication_year: 2024
publication_authors: L. Briand, T. Bontempelli, W. Bendada, M. Morlon, F. Rigaud, B. Chapus, T. Bouabça, G. Salha-Galvan
publication_conference: ECIR
publication_preprint: "https://arxiv.org/pdf/2401.02827"
publication_code: "https://github.com/deezer/new-releases-ecir2024"
---

Music artists release hundreds of thousands of new albums every week on the music streaming service Deezer. The prompt integration of this content, along with its swift discoverability through recommender systems and search engines, holds significant importance. For Deezer, it ensures that users have immediate access to the latest music of their favorite artists while also easily coming upon new ones they might like, which is known to improve the user experience. The proper exposure of new releases also benefits artists by amplifying their visibility, which can contribute to their success, boost their revenues, and foster the emergence of new talents. Nonetheless, displaying the right releases to the right users remains challenging due to the limited prior information on this fresh content, especially for new artists unknown from the service.

In this paper, we present our recent efforts to better showcase new releases on Deezer, both in terms of recommendation performance and number of new releases exposed to users. Specifically, we first focus on the product context. We describe in Section 2 our search and recommendation features dedicated to new releases, along with their objectives and differences. We also dive into our historical semi-personalized solution for new release recommendation, based on editorial pre-selections, and its limitations in terms of catalog coverage and adaptability. Then, in Section 3, we detail the fully personalized systems we deployed in 2023 to overcome these limitations, involving a cold start neural embedding model along with contextual bandits. We provide an online evaluation of our approach on Deezer's "New releases for you" carousel of recommended new albums. Finally, we conclude in Section 4 by discussing our ongoing efforts to improve our models and how we present new releases on the Deezer homepage.

<div class="publication-illustration">
    <img
        style="width: 70%;"
        src="{{ '/static/images/publis/briand24ecir/carousel.png' | prepend: site.url }}"
        alt="Let’s Get It Started: Fostering the Discoverability of New Releases on Deezer"/>
</div>

This paper has been accepted for publication in the proceedings of the 46th European Conference on Information Retrieval (ECIR 2024) at the Industry Day, and received the Best Industry Paper award.
