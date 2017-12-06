---
layout: post
title: "Relief R-CNN : Utilizing Convolutional Features for Fast Object Detection"
date: 2017-04-26 07:12:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Guiying Li, Junlong Liu, Chunhui Jiang, Liangpeng Zhang, Minlong Lin, Ke Tang
mathjax: true
---

* content
{:toc}

##### Abstract
R-CNN style methods are sorts of the state-of-the-art object detection methods, which consist of region proposal generation and deep CNN classification. However, the proposal generation phase in this paradigm is usually time consuming, which would slow down the whole detection time in testing. This paper suggests that the value discrepancies among features in deep convolutional feature maps contain plenty of useful spatial information, and proposes a simple approach to extract the information for fast region proposal generation in testing. The proposed method, namely Relief R-CNN (R2-CNN), adopts a novel region proposal generator in a trained R-CNN style model. The new generator directly generates proposals from convolutional features by some simple rules, thus resulting in a much faster proposal generation speed and a lower demand of computation resources. Empirical studies show that R2-CNN could achieve the fastest detection speed with comparable accuracy among all the compared algorithms in testing.

##### Abstract (translated by Google)
R-CNN风格的方法是一种最先进的对象检测方法，由区域提案生成和深度CNN分类组成。然而，这个范例中的建议生成阶段通常是耗时的，这将减慢测试的整个检测时间。本文提出，深卷积特征地图中的特征值差异包含了大量有用的空间信息，并提出了一种简单的方法来提取测试中快速区域提议生成的信息。所提出的方法，即Relief R-CNN（R2-CNN），在训练的R-CNN风格模型中采用了新的区域提议生成器。新的发生器通过一些简单的规则直接从卷积特征生成提议，从而导致提交生成速度更快，计算资源需求更低。实证研究表明，在所有比较算法的测试中，R2-CNN可以达到最快的检测速度，精确度相当。

##### URL
[https://arxiv.org/abs/1601.06719](https://arxiv.org/abs/1601.06719)

