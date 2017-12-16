---
layout: post
title: "Hyperspectral Image Classification with Markov Random Fields and a Convolutional Neural Network"
date: 2017-11-12 15:48:49
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Xiangyong Cao, Feng Zhou, Lin Xu, Deyu Meng, Zongben Xu, John Paisley
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new supervised classification algorithm for remotely sensed hyperspectral image (HSI) which integrates spectral and spatial information in a unified Bayesian framework. First, we formulate the HSI classification problem from a Bayesian perspective. Then, we adopt a convolutional neural network (CNN) to learn the posterior class distributions using a patch-wise training strategy to better use the spatial information. Next, spatial information is further considered by placing a spatial smoothness prior on the labels. Finally, we iteratively update the CNN parameters using stochastic gradient decent (SGD) and update the class labels of all pixel vectors using an alpha-expansion min-cut-based algorithm. Compared with other state-of-the-art methods, the proposed classification method achieves better performance on one synthetic dataset and two benchmark HSI datasets in a number of experimental settings.

##### Abstract (translated by Google)
本文提出了一种新的基于统一贝叶斯框架的遥感高光谱遥感图像分类算法（HSI）。首先，我们从贝叶斯的角度来制定HSI分类问题。然后，我们采用卷积神经网络（CNN），以补丁式训练策略学习后验分布，以更好地利用空间信息。接下来，通过在标签之前放置空间平滑度来进一步考虑空间信息。最后，我们使用随机梯度下降（SGD）迭代更新CNN参数，并使用基于alpha扩展最小切割的算法更新所有像素矢量的类标签。与其他最先进的方法相比，所提出的分类方法在一个合成数据集和两个基准HSI数据集上获得了更好的性能。

##### URL
[https://arxiv.org/abs/1705.00727](https://arxiv.org/abs/1705.00727)

##### PDF
[https://arxiv.org/pdf/1705.00727](https://arxiv.org/pdf/1705.00727)

