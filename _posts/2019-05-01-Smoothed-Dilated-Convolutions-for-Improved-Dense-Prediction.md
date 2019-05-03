---
layout: post
title: "Smoothed Dilated Convolutions for Improved Dense Prediction"
date: 2019-05-01 23:04:40
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Zhengyang Wang, Shuiwang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Dilated convolutions, also known as atrous convolutions, have been widely explored in deep convolutional neural networks (DCNNs) for various dense prediction tasks. However, dilated convolutions suffer from the gridding artifacts, which hampers the performance. In this work, we propose two simple yet effective degridding methods by studying a decomposition of dilated convolutions. Unlike existing models, which explore solutions by focusing on a block of cascaded dilated convolutional layers, our methods address the gridding artifacts by smoothing the dilated convolution itself. In addition, we point out that the two degridding approaches are intrinsically related and define separable and shared (SS) operations, which generalize the proposed methods. We further explore SS operations in view of operations on graphs and propose the SS output layer, which is able to smooth the entire DCNNs by only replacing the output layer. We evaluate our degridding methods and the SS output layer thoroughly, and visualize the smoothing effect through effective receptive field analysis. Results show that our methods degridding yield consistent improvements on the performance of dense prediction tasks, while adding negligible amounts of extra training parameters. And the SS output layer improves the performance significantly and is very efficient in terms of number of training parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.08931](http://arxiv.org/abs/1808.08931)

##### PDF
[http://arxiv.org/pdf/1808.08931](http://arxiv.org/pdf/1808.08931)

