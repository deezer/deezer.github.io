---
layout: post
title: "Towards Rigorous Interpretations: a Formalisation of Feature Attribution"
date: 2021-05-09 10:00:00 +0100
category: Publication
author: dafchar
readtime: 6
people:
 - dafchar
 - rhennequin
publication_type: conference
publication_title: "Towards Rigorous Interpretations: a Formalisation of Feature Attribution"
publication_year: 2021
publication_authors: D. Afchar, R. Hennequin, V. Guigue
publication_conference: ICML
publication_preprint: "https://arxiv.org/pdf/2104.12437.pdf"
publication_code: "https://github.com/DariusAf/functional_attribution"
---

Feature attribution is often loosely presented as the process of selecting a subset of relevant features as a rationale of a prediction. 
Task-dependent by nature, precise definitions of responsibility encountered in the literature are however not always consistent. 
This lack of clarity stems from the fact that we usually do not have access to any notion of ground-truth attribution and from a more general debate on what good interpretations are.

<div class="publication-illustration">
    <img
        style="width: 75%;"
        src="{{ '/static/images/publis/afchar21icml/i_am_a_picture.png' | prepend: site.url }}"
        alt="This picture is the front image of our article. It represents five points"/>
</div>

In this paper we propose to formalise feature selection/attribution based on the concept of relaxed functional dependence.
In particular, we extend our notions to the instance-wise setting and derive necessary properties for candidate selection solutions, while leaving room for task-dependence.
By computing ground-truth attributions on synthetic datasets, we evaluate many state-of-the-art attribution methods and show that, even when optimised, some fail to verify the proposed properties and provide wrong solutions.

This paper will been published in the proceedings of the 38th International Conference on Machine Learning (ICML 2021).
