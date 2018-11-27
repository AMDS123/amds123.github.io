---
layout: post
title: "NDDR-CNN: Layer-wise Feature Fusing in Multi-Task CNN by Neural Discriminative Dimensionality Reduction"
date: 2018-11-25 19:15:47
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yuan Gao, Jiayi Ma, Mingbo Zhao, Alan L. Yuille, Wei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel Convolutional Neural Network (CNN) structure for general-purpose multi-task learning (MTL), which enables automatic feature fusing at every layer from different tasks. This is in contrast with the most widely used MTL CNN structures which empirically or heuristically share features on some specific layers (e.g., share all the features except the last convolutional layer). The proposed layerwise feature fusing scheme is formulated by combining existing CNN components in a novel way, with clear mathematical interpretability as discriminative dimensionality reduction, which is referred to as Neural Discriminative Dimensionality Reduction (NDDR). Specifically, we first concatenate features with the same spatial resolution from different tasks according to their channel dimension. Then, we show that the discriminative dimensionality reduction can be fulfilled by 1x1 Convolution, Batch Normalization, and Weight Decay in one CNN. The use of existing CNN components ensures the end-to-end training and the extensibility of the proposed NDDR layer to various state-of-the-art CNN architectures in a "plug-and-play" manner. The detailed ablation analysis shows that the proposed NDDR layer is easy to train and also robust to different hyperparameters. Experiments on different task sets with various base network architectures demonstrate the promising performance and desirable generalizability of our proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.08297](http://arxiv.org/abs/1801.08297)

##### PDF
[http://arxiv.org/pdf/1801.08297](http://arxiv.org/pdf/1801.08297)

