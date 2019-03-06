---
layout: post
title: "Massively Distributed SGD: ImageNet/ResNet-50 Training in a Flash"
date: 2019-03-05 09:18:09
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Hiroaki Mikami, Hisahiro Suganuma, Pongsakorn U-chupala, Yoshiki Tanaka, Yuichi Kageyama
mathjax: true
---

* content
{:toc}

##### Abstract
Scaling the distributed deep learning to a massive GPU cluster level is challenging due to the instability of the large mini-batch training and the overhead of the gradient synchronization. We address the instability of the large mini-batch training with batch-size control and label smoothing. We address the overhead of the gradient synchronization with 2D-Torus all-reduce. Specifically, 2D-Torus all-reduce arranges GPUs in a logical 2D grid and performs a series of collective operation in different orientations. These two techniques are implemented with Neural Network Libraries (NNL). We have successfully trained ImageNet/ResNet-50 in 122 seconds without significant accuracy loss on ABCI cluster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05233](http://arxiv.org/abs/1811.05233)

##### PDF
[http://arxiv.org/pdf/1811.05233](http://arxiv.org/pdf/1811.05233)

