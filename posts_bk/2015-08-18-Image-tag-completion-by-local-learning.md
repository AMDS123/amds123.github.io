---
layout: post
title: "Image tag completion by local learning"
date: 2015-08-18 06:22:42
categories: arXiv_CV
tags: arXiv_CV Optimization Prediction Gradient_Descent
author: Jingyan Wang, Yihua Zhou, Haoxiang Wang, Xiaohong Yang, Feng Yang, Austin Peterson
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of tag completion is to learn the missing tags of an image. In this paper, we propose to learn a tag scoring vector for each image by local linear learning. A local linear function is used in the neighborhood of each image to predict the tag scoring vectors of its neighboring images. We construct a unified objective function for the learning of both tag scoring vectors and local linear function parame- ters. In the objective, we impose the learned tag scoring vectors to be consistent with the known associations to the tags of each image, and also minimize the prediction error of each local linear function, while reducing the complexity of each local function. The objective function is optimized by an alternate optimization strategy and gradient descent methods in an iterative algorithm. We compare the proposed algorithm against different state-of-the-art tag completion methods, and the results show its advantages.

##### Abstract (translated by Google)
标签完成的问题是学习图像的缺失标签。在本文中，我们建议通过局部线性学习来学习每个图像的标记得分向量。在每个图像的邻域中使用局部线性函数来预测其邻近图像的标记得分向量。我们为标记评分向量和局部线性函数参数的学习构建一个统一的目标函数。在目标中，我们将学习到的标记评分向量与已知的每个图像标记的关联性相加，并且将每个局部线性函数的预测误差最小化，同时降低每个局部函数的复杂度。目标函数通过迭代算法中的替代优化策略和梯度下降方法进行优化。我们将所提出的算法与不同的最先进的标签完成方法进行比较，结果显示了它的优点。

##### URL
[https://arxiv.org/abs/1508.04224](https://arxiv.org/abs/1508.04224)

##### PDF
[https://arxiv.org/pdf/1508.04224](https://arxiv.org/pdf/1508.04224)

