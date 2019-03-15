---
layout: post
title: "Hyperdrive: A Multi-Chip Systolically Scalable Binary-Weight CNN Inference Engine"
date: 2019-03-14 11:15:37
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Renzo Andri, Lukas Cavigelli, Davide Rossi, Luca Benini
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved impressive results in computer vision and machine learning. Unfortunately, state-of-the-art networks are extremely compute and memory intensive which makes them unsuitable for mW-devices such as IoT end-nodes. Aggressive quantization of these networks dramatically reduces the computation and memory footprint. Binary-weight neural networks (BWNs) follow this trend, pushing weight quantization to the limit. Hardware accelerators for BWNs presented up to now have focused on core efficiency, disregarding I/O bandwidth and system-level efficiency that are crucial for deployment of accelerators in ultra-low power devices. We present Hyperdrive: a BWN accelerator dramatically reducing the I/O bandwidth exploiting a novel binary-weight streaming approach, which can be used for arbitrarily sized convolutional neural network architecture and input resolution by exploiting the natural scalability of the compute units both at chip-level and system-level by arranging Hyperdrive chips systolically in a 2D mesh while processing the entire feature map together in parallel. Hyperdrive achieves 4.3 TOp/s/W system-level efficiency (i.e., including I/Os)---3.1x higher than state-of-the-art BWN accelerators, even if its core uses resource-intensive FP16 arithmetic for increased robustness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.00623](http://arxiv.org/abs/1804.00623)

##### PDF
[http://arxiv.org/pdf/1804.00623](http://arxiv.org/pdf/1804.00623)

