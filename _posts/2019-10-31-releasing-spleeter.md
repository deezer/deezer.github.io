---
layout: post
title: "Spleeter: a fast and efficient music source separation tool with pre-trained models"
date: 2020-06-24 15:44:41 +0200
category: Publication
author: rhennequin
readtime: 6
projects:
 - Spleeter
people:
 - rhennequin
 - akhlif
 - fvoituret
 - mmoussallam
publication_type: journal
publication_title: "Spleeter: a fast and efficient music source separation tool with pre-trained models"
publication_year: 2020
publication_authors: R. Hennequin, A. Khlif, F. Voituret, M. Moussallam
publication_journal: "Journal of Open Source Software"
publication_preprint: "https://joss.theoj.org/papers/10.21105/joss.02154"
publication_code: "https://github.com/deezer/spleeter"
---
We present and release a new tool for music source separation with pre-trained models called **Spleeter**. It was designed with ease of use, separation performance and speed in mind. It is based on [Tensorflow](http://tensorflow.org) and makes it possible to:

* separate audio files into 2, 4 or 5 stems with a single command line using pre-trained models.
* train source separation models or fine-tune pre-trained ones with Tensorflow (provided you have a dataset of isolated sources).

<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="https://raw.githubusercontent.com/deezer/spleeter/master/images/spleeter_logo.png"
        alt="spleeter_logo"/>
</div>

The performance of the pre-trained models are very close to the published state of the art and is, to the authors knowledge, the best performing 4 stems separation model on the common [musdb18 benchmark](https://sigsep.github.io/datasets/musdb.html) to be publicly released. **Spleeter** is also very fast as it can separate a mix audio file into 4 stems 100 times faster than real-time on a single GPU using the pre-trained 4-stems model.

We have released a [longer blog post](https://deezer.io/releasing-spleeter-deezer-r-d-source-separation-engine-2b88985e797e) about **Spleeter** and there has been nice reviews in the press. Notably on [TheVerge.com](https://www.theverge.com/2019/11/5/20949338/vocal-isolation-ai-machine-learning-deezer-spleeter-automated-open-source-tensorflow) (EN), [Gigazine.net](https://gigazine.net/news/20191107-spleeter/) (JP) and [RollingStone.fr](https://www.rollingstone.fr/deezer-spleeter/) (FR)