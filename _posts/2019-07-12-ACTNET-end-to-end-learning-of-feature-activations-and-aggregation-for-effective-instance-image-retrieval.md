---
layout: post
title: "ACTNET: end-to-end learning of feature activations and aggregation for effective instance image retrieval"
date: 2019-07-12 15:24:40
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge CNN
author: Syed Sameed Husain, Eng-Jon Ong, Miroslaw Bober
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel CNN architecture called ACTNET for robust instance image retrieval from large-scale datasets. Our key innovation is a learnable activation layer designed to improve the signal-to-noise ratio (SNR) of deep convolutional feature maps. This works in tandem with multi-stream aggregation, where complementary deep features from different convolutional layers are transformed and balanced, using our novel activation layer, before aggregation into a global descriptor. Importantly, the learnable parameters of activation blocks are explicitly trained, jointly with the CNN parameters, in an end-to-end manner minimising triplet loss. This means that our network jointly learns the CNN filters and their optimal aggregation for the retrieval task. To our knowledge, this is the first time parametric functions are used to control and learn optimal aggregation. We conduct an in-depth experimental study on three non-linear activation functions: Sine-Hyperbolic, Exponential and modified Weibull, showing that while all bring significant gains the Weibull function performs best thanks to its ability to equalise strong activations. The results clearly demonstrate that activation functions significantly enhance the discriminative power of deep features, leading to state-of-the-art retrieval results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05794](http://arxiv.org/abs/1907.05794)

##### PDF
[http://arxiv.org/pdf/1907.05794](http://arxiv.org/pdf/1907.05794)

