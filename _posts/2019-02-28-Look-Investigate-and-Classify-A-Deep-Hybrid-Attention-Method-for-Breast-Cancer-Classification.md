---
layout: post
title: "Look, Investigate, and Classify: A Deep Hybrid Attention Method for Breast Cancer Classification"
date: 2019-02-28 08:24:24
categories: arXiv_CV
tags: arXiv_CV Attention Classification Deep_Learning
author: Bolei Xu, Jingxin Liu, Xianxu Hou, Bozhi Liu, Jon Garibaldi, Ian O. Ellis, Andy Green, Linlin Shen, Guoping Qiu
mathjax: true
---

* content
{:toc}

##### Abstract
One issue with computer based histopathology image analysis is that the size of the raw image is usually very large. Taking the raw image as input to the deep learning model would be computationally expensive while resizing the raw image to low resolution would incur information loss. In this paper, we present a novel deep hybrid attention approach to breast cancer classification. It first adaptively selects a sequence of coarse regions from the raw image by a hard visual attention algorithm, and then for each such region it is able to investigate the abnormal parts based on a soft-attention mechanism. A recurrent network is then built to make decisions to classify the image region and also to predict the location of the image region to be investigated at the next time step. As the region selection process is non-differentiable, we optimize the whole network through a reinforcement approach to learn an optimal policy to classify the regions. Based on this novel Look, Investigate and Classify approach, we only need to process a fraction of the pixels in the raw image resulting in significant saving in computational resources without sacrificing performances. Our approach is evaluated on a public breast cancer histopathology database, where it demonstrates superior performance to the state-of-the-art deep learning approaches, achieving around 96\% classification accuracy while only 15% of raw pixels are used.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10946](http://arxiv.org/abs/1902.10946)

##### PDF
[http://arxiv.org/pdf/1902.10946](http://arxiv.org/pdf/1902.10946)

