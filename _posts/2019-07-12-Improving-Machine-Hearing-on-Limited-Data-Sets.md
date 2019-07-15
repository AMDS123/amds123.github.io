---
layout: post
title: "Improving Machine Hearing on Limited Data Sets"
date: 2019-07-12 13:20:13
categories: arXiv_SD
tags: arXiv_SD CNN
author: Pavol Harar, Roswitha Bammer, Anna Breger, Monika D&#xf6;rfler, Zdenek Smekal
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network (CNN) architectures have originated and revolutionized machine learning for images. In order to take advantage of CNNs in predictive modeling with audio data, standard FFT-based signal processing methods are often applied to convert the raw audio waveforms into an image-like representations (e.g. spectrograms). Even though conventional images and spectrograms differ in their feature properties, this kind of pre-processing reduces the amount of training data necessary for successful training. In this contribution we investigate how input and target representations interplay with the amount of available training data in a music information retrieval setting. We compare the standard mel-spectrogram inputs with a newly proposed representation, called Mel scattering. Furthermore, we investigate the impact of additional target data representations by using an augmented target loss function which incorporates unused available information. We observe that all proposed methods outperform the standard mel-transform representation when using a limited data set and discuss their strengths and limitations. The source code for reproducibility of our experiments as well as intermediate results and model checkpoints are available in an online repository.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08950](http://arxiv.org/abs/1903.08950)

##### PDF
[http://arxiv.org/pdf/1903.08950](http://arxiv.org/pdf/1903.08950)

