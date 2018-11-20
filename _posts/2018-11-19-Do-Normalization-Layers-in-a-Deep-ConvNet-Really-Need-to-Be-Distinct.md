---
layout: post
title: "Do Normalization Layers in a Deep ConvNet Really Need to Be Distinct?"
date: 2018-11-19 14:36:25
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning
author: Ping Luo, Zhanglin Peng, Jiamin Ren, Ruimao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Yes, they do. This work investigates a perspective for deep learning: whether different normalization layers in a ConvNet require different normalizers. This is the first step towards understanding this phenomenon. We allow each convolutional layer to be stacked before a switchable normalization (SN) that learns to choose a normalizer from a pool of normalization methods. Through systematic experiments in ImageNet, COCO, Cityscapes, and ADE20K, we answer three questions: (a) Is it useful to allow each normalization layer to select its own normalizer? (b) What impacts the choices of normalizers? (c) Do different tasks and datasets prefer different normalizers? Our results suggest that (1) using distinct normalizers improves both learning and generalization of a ConvNet; (2) the choices of normalizers are more related to depth and batch size, but less relevant to parameter initialization, learning rate decay, and solver; (3) different tasks and datasets have different behaviors when learning to select normalizers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07727](http://arxiv.org/abs/1811.07727)

##### PDF
[http://arxiv.org/pdf/1811.07727](http://arxiv.org/pdf/1811.07727)

