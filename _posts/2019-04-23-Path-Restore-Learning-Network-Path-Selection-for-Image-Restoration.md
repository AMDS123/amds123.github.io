---
layout: post
title: "Path-Restore: Learning Network Path Selection for Image Restoration"
date: 2019-04-23 14:07:11
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN
author: Ke Yu, Xintao Wang, Chao Dong, Xiaoou Tang, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
Very deep Convolutional Neural Networks (CNNs) have greatly improved the performance on various image restoration tasks. However, this comes at a price of increasing computational burden, which limits their practical usages. We believe that some corrupted image regions are inherently easier to restore than others since the distortion and content vary within an image. To this end, we propose Path-Restore, a multi-path CNN with a pathfinder that could dynamically select an appropriate route for each image region. We train the pathfinder using reinforcement learning with a difficulty-regulated reward, which is related to the performance, complexity and "the difficulty of restoring a region". We conduct experiments on denoising and mixed restoration tasks. The results show that our method could achieve comparable or superior performance to existing approaches with less computational cost. In particular, our method is effective for real-world denoising, where the noise distribution varies across different regions of a single image. We surpass the state-of-the-art CBDNet by 0.94 dB and run 29% faster on the realistic Darmstadt Noise Dataset. Models and codes will be released.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10343](http://arxiv.org/abs/1904.10343)

##### PDF
[http://arxiv.org/pdf/1904.10343](http://arxiv.org/pdf/1904.10343)

