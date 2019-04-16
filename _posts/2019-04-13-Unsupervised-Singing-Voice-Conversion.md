---
layout: post
title: "Unsupervised Singing Voice Conversion"
date: 2019-04-13 20:07:58
categories: arXiv_SD
tags: arXiv_SD Embedding Deep_Learning
author: Eliya Nachmani, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep learning method for singing voice conversion. The proposed network is not conditioned on the text or on the notes, and it directly converts the audio of one singer to the voice of another. Training is performed without any form of supervision: no lyrics or any kind of phonetic features, no notes, and no matching samples between singers. The proposed network employs a single CNN encoder for all singers, a single WaveNet decoder, and a classifier that enforces the latent representation to be singer-agnostic. Each singer is represented by one embedding vector, which the decoder is conditioned on. In order to deal with relatively small datasets, we propose a new data augmentation scheme, as well as new training losses and protocols that are based on backtranslation. Our evaluation presents evidence that the conversion produces natural signing voices that are highly recognizable as the target singer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06590](http://arxiv.org/abs/1904.06590)

##### PDF
[http://arxiv.org/pdf/1904.06590](http://arxiv.org/pdf/1904.06590)

