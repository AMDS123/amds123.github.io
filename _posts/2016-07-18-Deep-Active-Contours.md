---
layout: post
title: "Deep Active Contours"
date: 2016-07-18 13:53:29
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Christian Rupprecht, Elizabeth Huaroc, Maximilian Baust, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for interactive boundary extraction which combines a deep, patch-based representation with an active contour framework. We train a class-specific convolutional neural network which predicts a vector pointing from the respective point on the evolving contour towards the closest point on the boundary of the object of interest. These predictions form a vector field which is then used for evolving the contour by the Sobolev active contour framework proposed by Sundaramoorthi et al. The resulting interactive segmentation method is very efficient in terms of required computational resources and can even be trained on comparatively small graphics cards. We evaluate the potential of the proposed method on both medical and non-medical challenge data sets, such as the STACOM data set and the PASCAL VOC 2012 data set.

##### Abstract (translated by Google)
我们提出了一种交互式边界提取方法，该方法将深度的基于补丁的表示与活动轮廓框架相结合。我们训练一个特定类别的卷积神经网络，预测一个矢量从演化轮廓上的相应点指向感兴趣对象边界上的最近点。这些预测形成一个矢量场，然后用于由Sundaramoorthi等人提出的Sobolev主动轮廓框架演化轮廓。由此产生的交互式分割方法在所需的计算资源方面非常高效，甚至可以在相对较小的图形卡上进行培训。我们评估了该方法在医学和非医学挑战数据集（如STACOM数据集和PASCAL VOC 2012数据集）上的潜力。

##### URL
[https://arxiv.org/abs/1607.05074](https://arxiv.org/abs/1607.05074)

##### PDF
[https://arxiv.org/pdf/1607.05074](https://arxiv.org/pdf/1607.05074)

