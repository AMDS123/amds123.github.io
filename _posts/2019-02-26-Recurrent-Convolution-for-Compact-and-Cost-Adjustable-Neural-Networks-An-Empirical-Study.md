---
layout: post
title: "Recurrent Convolution for Compact and Cost-Adjustable Neural Networks: An Empirical Study"
date: 2019-02-26 09:09:24
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Inference Classification
author: Zhendong Zhang, Cheolkon Jung
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent convolution (RC) shares the same convolutional kernels and unrolls them multiple steps, which is originally proposed to model time-space signals. We argue that RC can be viewed as a model compression strategy for deep convolutional neural networks. RC reduces the redundancy across layers. However, the performance of an RC network is not satisfactory if we directly unroll the same kernels multiple steps. We propose a simple yet effective variant which improves the RC networks: the batch normalization layers of an RC module are learned independently (not shared) for different unrolling steps. Moreover, we verify that RC can perform cost-adjustable inference which is achieved by varying its unrolling steps. We learn double independent BN layers for cost-adjustable RC networks, i.e. independent w.r.t both the unrolling steps of current cell and upstream cell. We provide insights on why the proposed method works successfully. Experiments on both image classification and image denoise demonstrate the effectiveness of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09809](http://arxiv.org/abs/1902.09809)

##### PDF
[http://arxiv.org/pdf/1902.09809](http://arxiv.org/pdf/1902.09809)

