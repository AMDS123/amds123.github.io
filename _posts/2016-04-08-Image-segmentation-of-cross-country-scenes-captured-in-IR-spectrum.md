---
layout: post
title: "Image segmentation of cross-country scenes captured in IR spectrum"
date: 2016-04-08 20:14:46
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Tracking
author: Artem Lenskiy
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision has become a major source of information for autonomous navigation of robots of various types, self-driving cars, military robots and mars/lunar rovers are some examples. Nevertheless, the majority of methods focus on analysing images captured in visible spectrum. In this manuscript we elaborate on the problem of segmenting cross-country scenes captured in IR spectrum. For this purpose we proposed employing salient features. Salient features are robust to variations in scale, brightness and view angle. We suggest the Speeded-Up Robust Features as a basis for our salient features for a number of reasons discussed in the paper. We also provide a comparison of two SURF implementations. The SURF features are extracted from images of different terrain types. For every feature we estimate a terrain class membership function. The membership values are obtained by means of either the multi-layer perceptron or nearest neighbours. The features' class membership values and their spatial positions are then applied to estimate class membership values for all pixels in the image. To decrease the effect of segmentation blinking that is caused by rapid switching between different terrain types and to speed up segmentation, we are tracking camera position and predict features' positions. The comparison of the multi-layer perception and the nearest neighbour classifiers is presented in the paper. The error rate of the terrain segmentation using the nearest neighbours obtained on the testing set is 16.6+-9.17%.

##### Abstract (translated by Google)
计算机视觉已经成为各类机器人自主导航信息的主要来源，例如自驾车，军用机器人和火星/月球车等。尽管如此，大多数方法的重点是分析可见光谱中捕获的图像。在这个手稿中，我们详细阐述了在红外光谱中捕捉到的分割越野场景的问题。为此我们提出采用显着特征。显着的特点是稳健的规模，亮度和视角的变化。由于本文讨论的一些原因，我们建议将加速特性作为我们显着特性的基础。我们还提供了两个SURF实现的比较。 SURF特征是从不同地形类型的图像中提取的。对于每个特征，我们估计一个地形类的隶属函数。成员值是通过多层感知器或最近的邻居获得的。然后将特征的类别成员值和它们的空间位置应用于估计图像中所有像素的类别成员值。为了减少不同地形类型之间快速切换引起的分割闪烁的影响，加快分割速度，我们正在跟踪摄像机的位置和预测特征的位置。提出了多层感知与最近邻分类器的比较。使用测试集上获得的最近邻的地形分割的误差率为16.6±9.17％。

##### URL
[https://arxiv.org/abs/1604.02469](https://arxiv.org/abs/1604.02469)

##### PDF
[https://arxiv.org/pdf/1604.02469](https://arxiv.org/pdf/1604.02469)

