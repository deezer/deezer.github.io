---
name: Spleeter
category: Opensource project
description: |
    <i>Spleeter</i> is the <a href="https://www.deezer.com">Deezer</a> source separation library
    with pretrained models written in <a href="https://www.python.org">Python</a> and using
    <a href="https://www.tensorflow.org">Tensorflow</a>. It makes it easy to train music source
    separation models (assuming you have a dataset of isolated sources), and provides already
    trained state of the art models for performing various flavours of separation. Solution for professional using spleeter models are presented on the <a href="https://www.deezer-techservices.com/solutions/spleeter/">Deezer Tech Services website</a>
website: https://github.com/deezer/spleeter
partners:
    - label: Deezer Blog
      url: https://deezer.io/releasing-spleeter-deezer-r-d-source-separation-engine-2b88985e797e
    - label: Tech Services
      url: https://www.deezer-techservices.com/solutions/spleeter/
---
<div class="publication-illustration">
    <img
        style="width: 50%;"
        src="https://raw.githubusercontent.com/deezer/spleeter/master/images/spleeter_logo.png"
        alt="spleeter_logo"/>
</div>
The models available are:
<ul>
    <li>Vocals (singing voice) / accompaniment separation (2 stems)</li>
    <li>Vocals / drums / bass / other separation (4 stems)</li>
    <li>Vocals / drums / bass / piano / other separation (5 stems)</li>
</ul>
<p>
    2 stems and 4 stems models have state of the art performances on the musdb dataset. Spleeter is
    also very fast as it can perform separation of audio files to 4 stems 100x faster than real-time
    when run on a GPU.
</p>
<p>
    We designed Spleeter so you can use it straight from command line as well as directly in your own
    development pipeline as a Python library. It can be installed with Conda, with pip or be used with
    Docker.
</p>
