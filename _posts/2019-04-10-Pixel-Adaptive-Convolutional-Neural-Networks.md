---
layout: post
title: "Pixel-Adaptive Convolutional Neural Networks"
date: 2019-04-10 18:02:54
categories: arXiv_CV
tags: arXiv_CV CNN
author: Hang Su, Varun Jampani, Deqing Sun, Orazio Gallo, Erik Learned-Miller, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutions are the fundamental building block of CNNs. The fact that their weights are spatially shared is one of the main reasons for their widespread use, but it also is a major limitation, as it makes convolutions content agnostic. We propose a pixel-adaptive convolution (PAC) operation, a simple yet effective modification of standard convolutions, in which the filter weights are multiplied with a spatially-varying kernel that depends on learnable, local pixel features. PAC is a generalization of several popular filtering techniques and thus can be used for a wide range of use cases. Specifically, we demonstrate state-of-the-art performance when PAC is used for deep joint image upsampling. PAC also offers an effective alternative to fully-connected CRF (Full-CRF), called PAC-CRF, which performs competitively, while being considerably faster. In addition, we also demonstrate that PAC can be used as a drop-in replacement for convolution layers in pre-trained networks, resulting in consistent performance improvements.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05373](http://arxiv.org/abs/1904.05373)

##### PDF
[http://arxiv.org/pdf/1904.05373](http://arxiv.org/pdf/1904.05373)

