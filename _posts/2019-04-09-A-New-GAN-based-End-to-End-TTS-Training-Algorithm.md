---
layout: post
title: "A New GAN-based End-to-End TTS Training Algorithm"
date: 2019-04-09 16:37:35
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Transfer_Learning
author: Haohan Guo, Frank K. Soong, Lei He, Lei Xie
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end, autoregressive model-based TTS has shown significant performance improvements over the conventional one. However, the autoregressive module training is affected by the exposure bias, or the mismatch between the different distributions of real and predicted data. While real data is available in training, but in testing, only predicted data is available to feed the autoregressive module. By introducing both real and generated data sequences in training, we can alleviate the effects of the exposure bias. We propose to use Generative Adversarial Network (GAN) along with the key idea of Professor Forcing in training. A discriminator in GAN is jointly trained to equalize the difference between real and predicted data. In AB subjective listening test, the results show that the new approach is preferred over the standard transfer learning with a CMOS improvement of 0.1. Sentence level intelligibility tests show significant improvement in a pathological test set. The GAN-trained new model is also more stable than the baseline to produce better alignments for the Tacotron output.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04775](http://arxiv.org/abs/1904.04775)

##### PDF
[http://arxiv.org/pdf/1904.04775](http://arxiv.org/pdf/1904.04775)

