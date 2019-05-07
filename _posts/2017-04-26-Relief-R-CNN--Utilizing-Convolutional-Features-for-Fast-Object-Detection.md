---
layout: post
title: "Relief R-CNN : Utilizing Convolutional Features for Fast Object Detection"
date: 2017-04-26 07:12:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Guiying Li, Junlong Liu, Chunhui Jiang, Liangpeng Zhang, Minlong Lin, Ke Tang
mathjax: true
---

* content
{:toc}

##### Abstract
R-CNN style methods are sorts of the state-of-the-art object detection methods, which consist of region proposal generation and deep CNN classification. However, the proposal generation phase in this paradigm is usually time consuming, which would slow down the whole detection time in testing. This paper suggests that the value discrepancies among features in deep convolutional feature maps contain plenty of useful spatial information, and proposes a simple approach to extract the information for fast region proposal generation in testing. The proposed method, namely Relief R-CNN (R2-CNN), adopts a novel region proposal generator in a trained R-CNN style model. The new generator directly generates proposals from convolutional features by some simple rules, thus resulting in a much faster proposal generation speed and a lower demand of computation resources. Empirical studies show that R2-CNN could achieve the fastest detection speed with comparable accuracy among all the compared algorithms in testing.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1601.06719](https://arxiv.org/abs/1601.06719)

##### PDF
[https://arxiv.org/pdf/1601.06719](https://arxiv.org/pdf/1601.06719)

