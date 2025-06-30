---
layout: post
title: "PeakNetFP: Peak-based Neural Audio Fingerprinting Robust to Extreme Time Stretching"
date: 2025-06-25 18:00:00 +0200
category: Publication
author: gcortes
readtime: 1
domains: 
 - MIR
people:
 - gcortes
 - bmartin
 - rhennequin
publication_type: conference
publication_title: "PeakNetFP: Peak-based Neural Audio Fingerprinting Robust to Extreme Time Stretching"
publication_year: 2025
publication_authors: Guillem Cortès-Sebastià, Benjamin Martin, Emilio Molina, Xavier Serra, Romain Hennequin
publication_conference: ISMIR
publication_code: "https://github.com/guillemcortes/peaknetfp"
publication_preprint: "https://arxiv.org/pdf/2506.21086"
---

This work introduces PeakNetFP, the first neural audio fingerprinting (AFP) system designed specifically around spectral peaks. This novel system is designed to leverage the sparse spectral coordinates typically computed by traditional peak-based AFP methods. PeakNetFP performs hierarchical point feature extraction techniques similar to the computer vision model PointNet++, and is trained using contrastive learning like in the state-of-the-art deep learning AFP, NeuralFP. This combination allows PeakNetFP to outperform conventional AFP systems and achieves comparable performance to NeuralFP when handling challenging time-stretched audio data. In extensive evaluation, PeakNetFP maintains a Top-1 hit rate of over 90% for stretching factors ranging from 50% to 200%. Moreover, PeakNetFP offers significant efficiency advantages: compared to NeuralFP, it has 100 times fewer parameters and uses 11 times smaller input data. These features make PeakNetFP a lightweight and efficient solution for AFP tasks where time stretching is involved. Overall, this system represents a promising direction for future AFP technologies, as it successfully merges the lightweight nature of peak-based AFP with the adaptability and pattern recognition capabilities of neural network-based approaches, paving the way for more scalable and efficient solutions in the field.

This paper is a joint work between Deezer Research, BMAT Licensing S.L., and the Music Technology Group at Universitat Pompeu Fabra.
