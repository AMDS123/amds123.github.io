---
layout: post
title: "Backward Reduction of CNN Models with Information Flow Analysis"
date: 2018-07-16 08:32:54
categories: arXiv_CV
tags: arXiv_CV
author: Yu-Hsun Lin, Chun-Nan Chou, Edward Y. Chang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes backward reduction, an algorithm that explores the compact CNN design from the information flow perspective. This algorithm can remove substantial non-zero weighting parameters (redundant neural channels) by considering the network dynamic behavior, which the traditional model compaction techniques cannot achieve, to reduce the size of a model. With the aid of our proposed algorithm, we achieve significant model reduction results of ResNet-34 in ImageNet scale (32.3% reduction), which is 3X better than the state-of-the-art result (10.8%). Even for highly optimized models like SqueezeNet and MobileNet, we still achieve additional 10.81% and 37.56% reduction, respectively, with negligible performance degradation.

##### Abstract (translated by Google)
本文提出了一种从信息流角度探讨紧凑型CNN设计的后向约简算法。该算法通过考虑传统模型压缩技术无法实现的网络动态行为，可以去除大量的非零加权参数（冗余神经通道），以减小模型的大小。借助我们提出的算法，我们在ImageNet量表（32.3％减少）中实现了ResNet-34的显着模型减少结果，这比现有技术结果（10.8％）好3倍。即使对于像SqueezeNet和MobileNet这样高度优化的模型，我们仍然可以分别实现额外的10.81％和37.56％的降低，而性能降低可以忽略不计。

##### URL
[http://arxiv.org/abs/1807.05726](http://arxiv.org/abs/1807.05726)

##### PDF
[http://arxiv.org/pdf/1807.05726](http://arxiv.org/pdf/1807.05726)

