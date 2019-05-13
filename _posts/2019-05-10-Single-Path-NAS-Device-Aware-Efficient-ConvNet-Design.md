---
layout: post
title: "Single-Path NAS: Device-Aware Efficient ConvNet Design"
date: 2019-05-10 13:23:48
categories: arXiv_CV
tags: arXiv_CV NAS CNN Image_Classification Inference Classification
author: Dimitrios Stamoulis, Ruizhou Ding, Di Wang, Dimitrios Lymberopoulos, Bodhi Priyantha, Jie Liu, Diana Marculescu
mathjax: true
---

* content
{:toc}

##### Abstract
Can we automatically design a Convolutional Network (ConvNet) with the highest image classification accuracy under the latency constraint of a mobile device? Neural Architecture Search (NAS) for ConvNet design is a challenging problem due to the combinatorially large design space and search time (at least 200 GPU-hours). To alleviate this complexity, we propose Single-Path NAS, a novel differentiable NAS method for designing device-efficient ConvNets in less than 4 hours. 1. Novel NAS formulation: our method introduces a single-path, over-parameterized ConvNet to encode all architectural decisions with shared convolutional kernel parameters. 2. NAS efficiency: Our method decreases the NAS search cost down to 8 epochs (30 TPU-hours), i.e., up to 5,000x faster compared to prior work. 3. On-device image classification: Single-Path NAS achieves 74.96% top-1 accuracy on ImageNet with 79ms inference latency on a Pixel 1 phone, which is state-of-the-art accuracy compared to NAS methods with similar latency (&lt;80ms).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04159](http://arxiv.org/abs/1905.04159)

##### PDF
[http://arxiv.org/pdf/1905.04159](http://arxiv.org/pdf/1905.04159)

