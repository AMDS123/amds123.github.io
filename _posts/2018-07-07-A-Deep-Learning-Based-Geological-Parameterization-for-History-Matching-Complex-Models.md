---
layout: post
title: "A Deep-Learning-Based Geological Parameterization for History Matching Complex Models"
date: 2018-07-07 20:34:04
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Optimization Deep_Learning Prediction
author: Yimin Liu, Wenyue Sun, Louis J. Durlofsky
mathjax: true
---

* content
{:toc}

##### Abstract
A new low-dimensional parameterization based on principal component analysis (PCA) and convolutional neural networks (CNN) is developed to represent complex geological models. The CNN-PCA method is inspired by recent developments in computer vision using deep learning. CNN-PCA can be viewed as a generalization of an existing optimization-based PCA (O-PCA) method. Both CNN-PCA and O-PCA entail post-processing a PCA model to better honor complex geological features. In CNN-PCA, rather than use a histogram-based regularization as in O-PCA, a new regularization involving a set of metrics for multipoint statistics is introduced. The metrics are based on summary statistics of the nonlinear filter responses of geological models to a pre-trained deep CNN. In addition, in the CNN-PCA formulation presented here, a convolutional neural network is trained as an explicit transform function that can post-process PCA models quickly. CNN-PCA is shown to provide both unconditional and conditional realizations that honor the geological features present in reference SGeMS geostatistical realizations for a binary channelized system. Flow statistics obtained through simulation of random CNN-PCA models closely match results for random SGeMS models for a demanding case in which O-PCA models lead to significant discrepancies. Results for history matching are also presented. In this assessment CNN-PCA is applied with derivative-free optimization, and a subspace randomized maximum likelihood method is used to provide multiple posterior models. Data assimilation and significant uncertainty reduction are achieved for existing wells, and physically reasonable predictions are also obtained for new wells. Finally, the CNN-PCA method is extended to a more complex non-stationary bimodal deltaic fan system, and is shown to provide high-quality realizations for this challenging example.

##### Abstract (translated by Google)
基于主成分分析（PCA）和卷积神经网络（CNN）的新的低维参数化被开发用于表示复杂的地质模型。 CNN-PCA方法的灵感来自于使用深度学习的计算机视觉的最新发展。 CNN-PCA可被视为现有基于优化的PCA（O-PCA）方法的概括。 CNN-PCA和O-PCA都需要对PCA模型进行后处理，以更好地支持复杂的地质特征。在CNN-PCA中，不是像在O-PCA中那样使用基于直方图的正则化，而是引入涉及多点统计的一组度量的新正则化。度量基于地质模型对预训练的深CNN的非线性滤波器响应的汇总统计。此外，在此处介绍的CNN-PCA公式中，卷积神经网络被训练为显式变换函数，可以快速后处理PCA模型。 CNN-PCA被证明可以提供无条件和条件实现，以实现二进制信道化系统的参考SGeMS地统计实现中存在的地质特征。通过模拟随机CNN-PCA模型获得的流量统计数据与随机SGeMS模型的结果紧密匹配，以满足O-PCA模型导致显着差异的严苛要求。还提供了历史匹配的结果。在该评估中，CNN-PCA应用无导数优化，并且子空间随机化最大似然法用于提供多个后验模型。现有井实现了数据同化和显着的不确定性降低，并且还获得了新井的物理合理预测。最后，CNN-PCA方法扩展到更复杂的非固定双峰三角形风扇系统，并且被证明可以为这个具有挑战性的例子提供高质量的实现。

##### URL
[http://arxiv.org/abs/1807.02716](http://arxiv.org/abs/1807.02716)

##### PDF
[http://arxiv.org/pdf/1807.02716](http://arxiv.org/pdf/1807.02716)

