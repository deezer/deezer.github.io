---
layout: post
title: "Word2Vec applied to Recommendation: Hyperparameters Matter"
date: 2018-10-07 15:44:41 +0200
category: Publication
author: royo-letelier
readtime: 6
people:
 - royo-letelier

publication_type: conference
publication_title: "Word2Vec applied to Recommendation: Hyperparameters Matter"
publication_year: 2018
publication_authors: H. Caselles-Dupre, F. Lesaint, J. Royo-Letelier 
publication_conference: RecSys
publication_preprint: "https://arxiv.org/pdf/1804.04212.pdf"
publication_code: "https://github.com/deezer/w2v_reco_hyperparameters_matter"
---

Skip-gram with negative sampling, a popular variant of Word2vec
originally designed and tuned to create word embeddings for Natural Language Processing, has been used to create item embeddings
with successful applications in recommendation.

While these fields do not share the same type of data, neither evaluate on the same
tasks, recommendation applications tend to use the same already
tuned hyperparameters values, even if optimal hyperparameters values are often known to be data and task dependent. We thus investigate the marginal importance of each hyperparameter in a recommendation setting through large hyperparameter grid searches on various datasets.

Results reveal that optimizing neglected hyperparameters, namely negative sampling distribution, number of
epochs, subsampling parameter and window-size, significantly improves performance on a recommendation task, and can increase it
by an order of magnitude. Importantly, we find that optimal hyperparameters configurations for Natural Language Processing tasks
and Recommendation tasks are noticeably different.

<div class="publication-illustration">
    <img
        src="{{ '/static/images/publis/dupre18recsys/prediction_table.png' | prepend: site.url }}"
        alt="Next Event Prediction"/>
</div>

This paper has been published in the proceedings of the 12th ACM Conference on Recommender Systems (RecSys 2018).
