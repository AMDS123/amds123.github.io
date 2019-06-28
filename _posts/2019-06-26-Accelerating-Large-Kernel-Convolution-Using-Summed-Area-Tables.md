---
layout: post
title: "Accelerating Large-Kernel Convolution Using Summed-Area Tables"
date: 2019-06-26 22:24:56
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Prediction
author: Linguang Zhang, Maciej Halber, Szymon Rusinkiewicz
mathjax: true
---

* content
{:toc}

##### Abstract
Expanding the receptive field to capture large-scale context is key to obtaining good performance in dense prediction tasks, such as human pose estimation. While many state-of-the-art fully-convolutional architectures enlarge the receptive field by reducing resolution using strided convolution or pooling layers, the most straightforward strategy is adopting large filters. This, however, is costly because of the quadratic increase in the number of parameters and multiply-add operations. In this work, we explore using learnable box filters to allow for convolution with arbitrarily large kernel size, while keeping the number of parameters per filter constant. In addition, we use precomputed summed-area tables to make the computational cost of convolution independent of the filter size. We adapt and incorporate the box filter as a differentiable module in a fully-convolutional neural network, and demonstrate its competitive performance on popular benchmarks for the task of human pose estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11367](http://arxiv.org/abs/1906.11367)

##### PDF
[http://arxiv.org/pdf/1906.11367](http://arxiv.org/pdf/1906.11367)

