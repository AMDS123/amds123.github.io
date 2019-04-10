---
layout: post
title: "Crossmodal Voice Conversion"
date: 2019-04-09 08:53:10
categories: arXiv_SD
tags: arXiv_SD Face Relation
author: Hirokazu Kameoka, Kou Tanaka, Aaron Valero Puche, Yasunori Ohishi, Takuhiro Kaneko
mathjax: true
---

* content
{:toc}

##### Abstract
Humans are able to imagine a person's voice from the person's appearance and imagine the person's appearance from his/her voice. In this paper, we make the first attempt to develop a method that can convert speech into a voice that matches an input face image and generate a face image that matches the voice of the input speech by leveraging the correlation between faces and voices. We propose a model, consisting of a speech converter, a face encoder/decoder and a voice encoder. We use the latent code of an input face image encoded by the face encoder as the auxiliary input into the speech converter and train the speech converter so that the original latent code can be recovered from the generated speech by the voice encoder. We also train the face decoder along with the face encoder to ensure that the latent code will contain sufficient information to reconstruct the input face image. We confirmed experimentally that a speech converter trained in this way was able to convert input speech into a voice that matched an input face image and that the voice encoder and face decoder can be used to generate a face image that matches the voice of the input speech.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04540](http://arxiv.org/abs/1904.04540)

##### PDF
[http://arxiv.org/pdf/1904.04540](http://arxiv.org/pdf/1904.04540)

