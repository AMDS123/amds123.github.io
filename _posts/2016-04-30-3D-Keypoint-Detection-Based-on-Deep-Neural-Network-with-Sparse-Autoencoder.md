---
layout: post
title: "3D Keypoint Detection Based on Deep Neural Network with Sparse Autoencoder"
date: 2016-04-30 15:47:28
categories: arXiv_CV
tags: arXiv_CV Sparse Face Deep_Learning Detection
author: Xinyu Lin, Ce Zhu, Qian Zhang, Yipeng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Researchers have proposed various methods to extract 3D keypoints from the surface of 3D mesh models over the last decades, but most of them are based on geometric methods, which lack enough flexibility to meet the requirements for various applications. In this paper, we propose a new method on the basis of deep learning by formulating the 3D keypoint detection as a regression problem using deep neural network (DNN) with sparse autoencoder (SAE) as our regression model. Both local information and global information of a 3D mesh model in multi-scale space are fully utilized to detect whether a vertex is a keypoint or not. SAE can effectively extract the internal structure of these two kinds of information and formulate high-level features for them, which is beneficial to the regression model. Three SAEs are used to formulate the hidden layers of the DNN and then a logistic regression layer is trained to process the high-level features produced in the third SAE. Numerical experiments show that the proposed DNN based 3D keypoint detection algorithm outperforms current five state-of-the-art methods for various 3D mesh models.

##### Abstract (translated by Google)
研究人员提出了几十年来从三维网格模型表面提取三维关键点的方法，但是大多数方法都是基于几何方法，缺乏足够的灵活性来满足各种应用的需求。本文在深度学习的基础上提出了一种新的基于深度神经网络（DNN）和稀疏自动编码器（SAE）作为回归模型的三维关键点检测算法。充分利用多尺度空间中的三维网格模型的局部信息和全局信息来检测顶点是否是关键点。 SAE可以有效地提取这两种信息的内部结构，为它们制定高层次的特征，这对回归模型是有利的。三个SAE被用于制定DNN的隐藏层，然后逻辑回归层被训练来处理在第三个SAE中产生的高级特征。数值实验表明，所提出的基于DNN的三维关键点检测算法优于当前五种最先进的方法对于各种三维网格模型。

##### URL
[https://arxiv.org/abs/1605.00129](https://arxiv.org/abs/1605.00129)

##### PDF
[https://arxiv.org/pdf/1605.00129](https://arxiv.org/pdf/1605.00129)

