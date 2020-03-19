---
layout: post
title: "Improving Collaborative Metric Learning with Efficient Negative Sampling"
date: 2019-07-21 15:44:41 +0200
category: Publication
author: vatran
readtime: 6
people:
 - rhennequin
 - mmoussallam
 - royo-letelier
 - vatran

publication_type: conference
publication_title: "Improving Collaborative Metric Learning with Efficient Negative Sampling"
publication_year: 2019
publication_authors: V-A. Tran, R. Hennequin, J. Royo-Letelier, M. Moussallam
publication_conference: SIGIR
publication_preprint: "https://arxiv.org/pdf/1909.10912.pdf"
publication_code: "https://github.com/deezer/sigir2019-2stagesampling"
---

Distance metric learning based on triplet loss has been applied with success in a wide range of applications such as face recognition, image retrieval, speaker change detection and recently recommendation with the Collaborative Metric Learnig (CML) model.

However, as we show in this article, CML requires large batches to work reasonably well because of a too simplistic uniform negative sampling strategy for selecting triplets. Due to the memory limitation, this makes it difficult to scale metric learning techniques in high-dimensional scenarios.

To alleviate this problem, we propose here a 2-stage negative sampling strategy which finds triplets that are more informative for learning. Our strategy allows CML to work effectively in terms of accuracy and popularity bias, even when the batch size is an order of magnitude smaller than what would be needed with the default uniform sampling. We demonstrate the suitability of the proposed strategy for recommendation and exhibit consistent positive results across various datasets.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/tran19sigir/uniform_strategy.png' | prepend: site.baseurl }}"
        alt="Performances"/>
</div>

This paper has been published in the proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2019).