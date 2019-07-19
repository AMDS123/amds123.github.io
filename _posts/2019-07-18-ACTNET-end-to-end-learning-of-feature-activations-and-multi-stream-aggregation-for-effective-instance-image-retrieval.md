---
layout: post
title: "ACTNET: end-to-end learning of feature activations and multi-stream aggregation for effective instance image retrieval"
date: 2019-07-18 13:00:25
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge CNN
author: Syed Sameed Husain, Eng-Jon Ong, Miroslaw Bober
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel CNN architecture called ACTNET for robust instance image retrieval from large-scale datasets. Our key innovation is a learnable activation layer designed to improve the signal-to-noise ratio (SNR) of deep convolutional feature maps. Further, we introduce a controlled multi-stream aggregation, where complementary deep features from different convolutional layers are optimally transformed and balanced using our novel activation layers, before aggregation into a global descriptor. Importantly, the learnable parameters of our activation blocks are explicitly trained, together with the CNN parameters, in an end-to-end manner minimising triplet loss. This means that our network jointly learns the CNN filters and their optimal activation and aggregation for retrieval tasks. To our knowledge, this is the first time parametric functions have been used to control and learn optimal aggregation. We conduct an in-depth experimental study on three non-linear activation functions: Sine-Hyperbolic, Exponential and modified Weibull, showing that while all bring significant gains the Weibull function performs best thanks to its ability to equalise strong activations. The results clearly demonstrate that our ACTNET architecture significantly enhances the discriminative power of deep features, improving significantly over the state-of-the-art retrieval results on all datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1907.05794](https://arxiv.org/abs/1907.05794)

##### PDF
[https://arxiv.org/pdf/1907.05794](https://arxiv.org/pdf/1907.05794)

