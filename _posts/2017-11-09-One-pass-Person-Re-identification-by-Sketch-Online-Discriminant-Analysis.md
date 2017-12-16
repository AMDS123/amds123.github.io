---
layout: post
title: "One-pass Person Re-identification by Sketch Online Discriminant Analysis"
date: 2017-11-09 13:29:33
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Embedding
author: Wei-Hong Li, Zhuowei Zhong, Wei-Shi Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-id) is to match people across disjoint camera views in a multi-camera system, and re-id has been an important technology applied in smart city in recent years. However, the majority of existing person re-id methods are not designed for processing sequential data in an online way. This ignores the real-world scenario that person images detected from multi-cameras system are coming sequentially. While there is a few work on discussing online re-id, most of them require considerable storage of all passed data samples that have been ever observed, and this could be unrealistic for processing data from a large camera network. In this work, we present an onepass person re-id model that adapts the re-id model based on each newly observed data and no passed data are directly used for each update. More specifically, we develop an Sketch online Discriminant Analysis (SoDA) by embedding sketch processing into Fisher discriminant analysis (FDA). SoDA can efficiently keep the main data variations of all passed samples in a low rank matrix when processing sequential data samples, and estimate the approximate within-class variance (i.e. within-class covariance matrix) from the sketch data information. We provide theoretical analysis on the effect of the estimated approximate within-class covariance matrix. In particular, we derive upper and lower bounds on the Fisher discriminant score (i.e. the quotient between between-class variation and within-class variation after feature transformation) in order to investigate how the optimal feature transformation learned by SoDA sequentially approximates the offline FDA that is learned on all observed data. Extensive experimental results have shown the effectiveness of our SoDA and empirically support our theoretical analysis.

##### Abstract (translated by Google)
个人重新识别（Re-id）是在多摄像机系统中通过不相交的摄像机视角匹配人，重新识别近年来一直是智能城市应用的重要技术。但是，大多数现有的人员重定义方法并不是为了以在线方式处理顺序数据而设计的。这忽略了从多摄像机系统检测到的人物图像依次出现的真实情景。尽管在讨论在线re-id方面有一些工作要做，但是其中大部分需要大量存储所有已经被观察过的数据样本，并且这对于处理来自大型相机网络的数据可能是不现实的。在这项工作中，我们提出了一个单通人员re-id模型，该模型基于每个新观察到的数据来调整re-id模型，并且没有传递的数据被直接用于每个更新。更具体地说，我们通过将草图处理嵌入Fisher判别分析（FDA）来开发草图在线判别分析（SoDA）。当处理连续的数据样本时，SoDA可以有效地将所有通过的样本的主要数据变化保持在低秩矩阵中，并且从草图数据信息中估计近似的类内方差（即，类别内协方差矩阵）。我们对估计的近似类内协方差矩阵的效果进行了理论分析。特别地，我们推导了Fisher判别分数（即特征变换后的类间变化和类内变化之间的商）的上下界，以研究SoDA学习的最优特征变换如何近似离线的FDA学习所有观察到的数据。广泛的实验结果显示了我们的SoDA的有效性，并且经验地支持了我们的理论分析。

##### URL
[https://arxiv.org/abs/1711.03368](https://arxiv.org/abs/1711.03368)

##### PDF
[https://arxiv.org/pdf/1711.03368](https://arxiv.org/pdf/1711.03368)

