---
layout: post
title: "Fitting 3D Morphable Models using Local Features"
date: 2015-03-08 21:57:49
categories: arXiv_CV
tags: arXiv_CV
author: Patrik Huber, Zhen-Hua Feng, William Christmas, Josef Kittler, Matthias Rätsch
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel fitting method that uses local image features to fit a 3D Morphable Model to 2D images. To overcome the obstacle of optimising a cost function that contains a non-differentiable feature extraction operator, we use a learning-based cascaded regression method that learns the gradient direction from data. The method allows to simultaneously solve for shape and pose parameters. Our method is thoroughly evaluated on Morphable Model generated data and first results on real data are presented. Compared to traditional fitting methods, which use simple raw features like pixel colour or edge maps, local features have been shown to be much more robust against variations in imaging conditions. Our approach is unique in that we are the first to use local features to fit a Morphable Model. Because of the speed of our method, it is applicable for realtime applications. Our cascaded regression framework is available as an open source library (this https URL).

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的拟合方法，使用局部图像特征来拟合二维图像的三维形状模型。为了克服优化包含不可微特征提取算子的成本函数的障碍，我们使用了一种基于学习的级联回归方法，从数据中学习梯度方向。该方法允许同时求解形状和姿态参数。对形变模型生成的数据进行了全面的评估，并给出了实际数据的初步结果。与使用像素颜色或边缘映射等简单原始特征的传统拟合方法相比，局部特征已被证明对成像条件的变化更为稳健。我们的方法是独一无二的，因为我们是第一个使用局部特征来拟合形变模型。由于我们的方法的速度，它适用于实时应用程序。我们的级联回归框架可以作为开源库（https https）来使用。

##### URL
[https://arxiv.org/abs/1503.02330](https://arxiv.org/abs/1503.02330)

##### PDF
[https://arxiv.org/pdf/1503.02330](https://arxiv.org/pdf/1503.02330)

