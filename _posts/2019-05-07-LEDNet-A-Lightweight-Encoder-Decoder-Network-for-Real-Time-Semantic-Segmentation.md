---
layout: post
title: "LEDNet: A Lightweight Encoder-Decoder Network for Real-Time Semantic Segmentation"
date: 2019-05-07 09:12:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Semantic_Segmentation
author: Yu Wang, Quan Zhou, Jia Liu, Jian Xiong, Guangwei Gao, Xiaofu Wu, Longin Jan Latecki
mathjax: true
---

* content
{:toc}

##### Abstract
The extensive computational burden limits the usage of CNNs in mobile devices for dense estimation tasks. In this paper, we present a lightweight network to address this problem,namely LEDNet, which employs an asymmetric encoder-decoder architecture for the task of real-time semantic segmentation.More specifically, the encoder adopts a ResNet as backbone network, where two new operations, channel split and shuffle, are utilized in each residual block to greatly reduce computation cost while maintaining higher segmentation accuracy. On the other hand, an attention pyramid network (APN) is employed in the decoder to further lighten the entire network complexity. Our model has less than 1M parameters,and is able to run at over 71 FPS in a single GTX 1080Ti GPU. The comprehensive experiments demonstrate that our approach achieves state-of-the-art results in terms of speed and accuracy trade-off on CityScapes dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02423](https://arxiv.org/abs/1905.02423)

##### PDF
[https://arxiv.org/pdf/1905.02423](https://arxiv.org/pdf/1905.02423)

