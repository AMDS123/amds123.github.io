---
layout: post
title: "A Distance Map Regularized CNN for Cardiac Cine MR Image Segmentation"
date: 2019-01-04 18:24:52
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN Semantic_Segmentation
author: Shusil Dangi, Ziv Yaniv, Cristian Linte
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac image segmentation is a critical process for generating personalized models of the heart and for quantifying cardiac performance parameters. Several convolutional neural network (CNN) architectures have been proposed to segment the heart chambers from cardiac cine MR images. Here we propose a multi-task learning (MTL)-based regularization framework for cardiac MR image segmentation. The network is trained to perform the main task of semantic segmentation, along with a simultaneous, auxiliary task of pixel-wise distance map regression. The proposed distance map regularizer is a decoder network added to the bottleneck layer of an existing CNN architecture, facilitating the network to learn robust global features. The regularizer block is removed after training, so that the original number of network parameters does not change. We show that the proposed regularization method improves both binary and multi-class segmentation performance over the corresponding state-of-the-art CNN architectures on two publicly available cardiac cine MRI datasets, obtaining average dice coefficient of 0.84$\pm$0.03 and 0.91$\pm$0.04, respectively. Furthermore, we also demonstrate improved generalization performance of the distance map regularized network on cross-dataset segmentation, showing as much as 41% improvement in average Dice coefficient from 0.57$\pm$0.28 to 0.80$\pm$0.13.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.01238](https://arxiv.org/abs/1901.01238)

##### PDF
[https://arxiv.org/pdf/1901.01238](https://arxiv.org/pdf/1901.01238)

