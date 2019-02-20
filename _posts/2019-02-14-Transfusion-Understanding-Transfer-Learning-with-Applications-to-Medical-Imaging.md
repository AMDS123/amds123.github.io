---
layout: post
title: "Transfusion: Understanding Transfer Learning with Applications to Medical Imaging"
date: 2019-02-14 01:54:53
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Deep_Learning Relation
author: Maithra Raghu, Chiyuan Zhang, Jon Kleinberg, Samy Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
With the increasingly varied applications of deep learning, transfer learning has emerged as a critically important technique. However, the central question of how much feature reuse in transfer is the source of benefit remains unanswered. In this paper, we present an in-depth analysis of the effects of transfer, focusing on medical imaging, which is a particularly intriguing setting. Here, transfer learning is extremely popular, but data differences between pretraining and finetuing are considerable, reiterating the question of what is transferred. With experiments on two large scale medical imaging datasets, and CIFAR-10, we find transfer has almost negligible effects on performance, but significantly helps convergence speed. However, in all of these settings, convergence without transfer can be sped up dramatically by using only mean and variance statistics of the pretrained weights. Visualizing the lower layer filters shows that models trained from random initialization do not learn Gabor filters on medical images. We use CCA (canonical correlation analysis) to study the learned representations of the different models, finding that pretrained models are surprisingly similar to random initialization at higher layers. This similarity is evidenced both through model learning dynamics and a transfusion experiment, which explores the convergence speed using a subset of pretrained weights.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07208](http://arxiv.org/abs/1902.07208)

##### PDF
[http://arxiv.org/pdf/1902.07208](http://arxiv.org/pdf/1902.07208)

