---
layout: post
title: Do Recommender Systems Promote Local Music? A Reproducibility Study Using Music Streaming Data
date: 2024-09-04 13:13:13 +0200
category: Publication
readtime: 6
author: kmatrosova
projects:
 - RECORDS
people:
 - kmatrosova
 - lmarey
 - gsalhagalvan
 - mmoussallam

publication_type: conference
publication_title: "Do Recommender Systems Promote Local Music? A Reproducibility Study Using Music Streaming Data"
publication_year: 2024
publication_authors: K. Matrosova, L. Marey, G. Salha-Galvan, T. Louail, O. Bodini, M. Moussallam
publication_conference: RecSys
publication_code: "https://github.com/kmatrosova/LocalMusicRecSys2024"
publication_preprint: "https://arxiv.org/pdf/2408.16430"
domains: 
 - RECSYS
---

This paper examines the influence of recommender systems on local music representation, discussing prior findings from an empirical study on the LFM-2b public dataset. This prior study argued that different recommender systems exhibit algorithmic biases shifting music consumption either towards or against local content.
However, LFM-2b users do not reflect the diverse audience of music streaming services. To assess the robustness of this study’s conclusions, we conduct a comparative analysis using proprietary listening data from a global music streaming service, which we
publicly release alongside this paper. 
We observe significant differences in local music consumption patterns between our dataset and LFM-2b, suggesting that caution should be exercised when drawing conclusions on local music based solely on LFM-2b. 
Moreover, we show that the algorithmic biases exhibited in the original work vary in our dataset, and that several unexplored model parameters can significantly influence these biases and affect the study’s conclusion
on both datasets. Finally, we discuss the complexity of accurately labeling local music, emphasizing the risk of misleading conclusions due to unreliable, biased, or incomplete labels. 
To encourage further research and ensure reproducibility, we have publicly shared our dataset and code.

This paper has been accepted at the 18th ACM Conference on Recommender Systems (RecSys 2024) in the Reproducibility Track.
