---
layout: post
title: "3D Dense Separated Convolution Module for Volumetric Image Analysis"
date: 2019-05-14 03:26:27
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Classification Deep_Learning
author: Lei Qu, Changfeng Wu, Liang Zou
mathjax: true
---

* content
{:toc}

##### Abstract
With the thriving of deep learning, 3D Convolutional Neural Networks have become a popular choice in volumetric image analysis due to their impressive 3D contexts mining ability. However, the 3D convolutional kernels will introduce a significant increase in the amount of trainable parameters. Considering the training data is often limited in biomedical tasks, a tradeoff has to be made between model size and its representational power. To address this concern, in this paper, we propose a novel 3D Dense Separated Convolution (3D-DSC) module to replace the original 3D convolutional kernels. The 3D-DSC module is constructed by a series of densely connected 1D filters. The decomposition of 3D kernel into 1D filters reduces the risk of over-fitting by removing the redundancy of 3D kernels in a topologically constrained manner, while providing the infrastructure for deepening the network. By further introducing nonlinear layers and dense connections between 1D filters, the network's representational power can be significantly improved while maintaining a compact architecture. We demonstrate the superiority of 3D-DSC on volumetric image classification and segmentation, which are two challenging tasks often encountered in biomedical image computing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08608](http://arxiv.org/abs/1905.08608)

##### PDF
[http://arxiv.org/pdf/1905.08608](http://arxiv.org/pdf/1905.08608)

