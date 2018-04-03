---
layout: post
title: "Hyperdrive: A Systolically Scalable Binary-Weight CNN Inference Engine for mW IoT End-Nodes"
date: 2018-03-05 17:35:42
categories: arXiv_CV
tags: arXiv_CV Inference
author: Renzo Andri, Lukas Cavigelli, Davide Rossi, Luca Benini
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved impressive results in computer vision and machine learning. Unfortunately, state-of-the-art networks are extremely compute- and memory-intensive which makes them unsuitable for mW-devices such as IoT end-nodes. Aggressive quantization of these networks dramatically reduces the computation and memory footprint. Binary-weight neural networks (BWNs) follow this trend, pushing weight quantization to the limit. Hardware accelerators for BWNs presented up to now have focused on core efficiency, disregarding I/O bandwidth and system-level efficiency that are crucial for deployment of accelerators in ultra-low power devices. We present Hyperdrive: a BWN accelerator dramatically reducing the I/O bandwidth exploiting a novel binary-weight streaming approach, and capable of handling high-resolution images by virtue of its systolic-scalable architecture. We achieve a 5.9 TOp/s/W system-level efficiency (i.e. including I/Os)---2.2x higher than state-of-the-art BNN accelerators, even if our core uses resource-intensive FP16 arithmetic for increased robustness.

##### Abstract (translated by Google)
深度神经网络在计算机视觉和机器学习中取得了令人瞩目的成果不幸的是，最先进的网络非常计算和内存密集，这使得它们不适用于诸如物联网终端节点之类的mW设备。这些网络的主动量化大大减少了计算和内存占用。二进制权重神经网络（BWN）遵循这一趋势，将重量量化推到极限。迄今为止提出的用于BWN的硬件加速器主要集中于核心效率，忽略了对于在超低功率器件中部署加速器至关重要的I / O带宽和系统级效率。我们介绍Hyperdrive：一种BWN加速器，通过采用新颖的二进制加权流方法大幅降低I / O带宽，并且凭借其可伸缩的体系结构能够处理高分辨率图像。即使我们的内核使用资源密集型FP16算法提高了鲁棒性，我们也实现了5.9 TOp / s / W系统级效率（即包括I / O） - 比现有BNN加速器高2.2倍。

##### URL
[http://arxiv.org/abs/1804.00623](http://arxiv.org/abs/1804.00623)

##### PDF
[http://arxiv.org/pdf/1804.00623](http://arxiv.org/pdf/1804.00623)

