---
layout: post
title: "No Fuss Distance Metric Learning using Proxies"
date: 2017-08-01 19:52:13
categories: arXiv_CV
tags: arXiv_CV Optimization Relation
author: Yair Movshovitz-Attias, Alexander Toshev, Thomas K. Leung, Sergey Ioffe, Saurabh Singh
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of distance metric learning (DML), defined as learning a distance consistent with a notion of semantic similarity. Traditionally, for this problem supervision is expressed in the form of sets of points that follow an ordinal relationship -- an anchor point $x$ is similar to a set of positive points $Y$, and dissimilar to a set of negative points $Z$, and a loss defined over these distances is minimized. While the specifics of the optimization differ, in this work we collectively call this type of supervision Triplets and all methods that follow this pattern Triplet-Based methods. These methods are challenging to optimize. A main issue is the need for finding informative triplets, which is usually achieved by a variety of tricks such as increasing the batch size, hard or semi-hard triplet mining, etc. Even with these tricks, the convergence rate of such methods is slow. In this paper we propose to optimize the triplet loss on a different space of triplets, consisting of an anchor data point and similar and dissimilar proxy points which are learned as well. These proxies approximate the original data points, so that a triplet loss over the proxies is a tight upper bound of the original loss. This proxy-based loss is empirically better behaved. As a result, the proxy-loss improves on state-of-art results for three standard zero-shot learning datasets, by up to 15% points, while converging three times as fast as other triplet-based losses.

##### Abstract (translated by Google)
我们解决了距离度量学习（DML）的问题，定义为学习与语义相似度概念一致的距离。传统上，对于这个问题，监督是以一系列的顺序关系来表示的 - 一个锚点$ x $类似于一组正数点$ Y $，不同于一组负的点数$ Z $，并且在这些距离上定义的损失被最小化。虽然优化的具体细节不同，但在这项工作中，我们统称为这种类型的监督三元组和所有遵循这种模式基于三元组的方法。这些方法是优化的挑战。一个主要的问题是需要寻找信息三元组，这通常是通过各种技巧来实现的，例如增加批量大小，硬或半硬三元组挖掘等等。即使有这些技巧，这种方法的收敛速度也很慢。在本文中，我们建议优化在不同空间的三元组的三重损失，包括一个锚点数据点和相似和不相似的代理点。这些代理接近原始数据点，因此代理的三重损失是原始损失的紧上限。这种基于代理的损失在经验上表现得更好。结果，三个标准零点学习数据集的最新结果的代理损失提高了15％，而收敛速度是其他三元组损失的三倍。

##### URL
[https://arxiv.org/abs/1703.07464](https://arxiv.org/abs/1703.07464)

##### PDF
[https://arxiv.org/pdf/1703.07464](https://arxiv.org/pdf/1703.07464)

