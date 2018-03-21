---
layout: post
title: "DUGMA: Dynamic Uncertainty-Based Gaussian Mixture Alignment"
date: 2018-03-18 13:06:24
categories: arXiv_CV
tags: arXiv_CV
author: Can Pu, Nanbo Li, Radim Tylecek, Robert B Fisher
mathjax: true
---

* content
{:toc}

##### Abstract
Registering accurately point clouds from a cheap low-resolution sensor is a challenging task. Existing rigid registration methods failed to use the physical 3D uncertainty distribution of each point from a real sensor in the dynamic alignment process mainly because the uncertainty model for a point is static and invariant and it is hard to describe the change of these physical uncertainty models in the registration process. Additionally, the existing Gaussian mixture alignment architecture cannot be efficiently implement these dynamic changes. 
 This paper proposes a simple architecture combining error estimation from sample covariances and dual dynamic global probability alignment using the convolution of uncertainty-based Gaussian Mixture Models (GMM) from point clouds. Firstly, we propose an efficient way to describe the change of each 3D uncertainty model, which represents the structure of the point cloud much better. Unlike the invariant GMM (representing a fixed point cloud) in traditional Gaussian mixture alignment, we use two uncertainty-based GMMs that change and interact with each other in each iteration. In order to have a wider basin of convergence than other local algorithms, we design a more robust energy function by convolving efficiently the two GMMs over the whole 3D space. 
 Tens of thousands of trials have been conducted on hundreds of models from multiple datasets to demonstrate the proposed method's superior performance compared with the current state-of-the-art methods. The new dataset and code is available from https://github.com/Canpu999

##### Abstract (translated by Google)
准确地从廉价的低分辨率传感器注册点云是一项具有挑战性的任务。现有的刚性配准方法未能在动态调整过程中使用来自真实传感器的每个点的物理3D不确定性分布，这主要是因为点的不确定性模型是静态且不变的，并且很难描述这些物理不确定性模型在注册过程。另外，现有的高斯混合对准架构不能有效地实现这些动态变化。
 本文提出了一种简单的体系结构，该体系结合了来自样本协方差的误差估计和使用来自点云的基于不确定性的高斯混合模型（GMM）的卷积的双动态全局概率比对。首先，我们提出一种描述每个三维不确定性模型变化的有效方法，它更好地表示了点云的结构。与传统高斯混合对齐中的不变GMM（代表固定点云）不同，我们使用两个基于不确定性的GMM，它们在每次迭代中相互变化并相互作用。为了比其他局部算法有更广泛的收敛盆地，我们通过在整个三维空间有效地卷积两个GMM来设计更强大的能量函数。
 已经对来自多个数据集的数百个模型进行了数万次试验，以证明所提出的方法与当前最先进的方法相比的优越性能。新的数据集和代码可从https://github.com/Canpu999获取

##### URL
[http://arxiv.org/abs/1803.07426](http://arxiv.org/abs/1803.07426)

##### PDF
[http://arxiv.org/pdf/1803.07426](http://arxiv.org/pdf/1803.07426)

