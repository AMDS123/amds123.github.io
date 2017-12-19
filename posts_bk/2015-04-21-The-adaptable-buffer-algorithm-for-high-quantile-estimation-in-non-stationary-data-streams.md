---
layout: post
title: "The adaptable buffer algorithm for high quantile estimation in non-stationary data streams"
date: 2015-04-21 04:42:58
categories: arXiv_CV
tags: arXiv_CV
author: Ognjen Arandjelovic, Duc-Son Pham, Svetha Venkatesh
mathjax: true
---

* content
{:toc}

##### Abstract
The need to estimate a particular quantile of a distribution is an important problem which frequently arises in many computer vision and signal processing applications. For example, our work was motivated by the requirements of many semi-automatic surveillance analytics systems which detect abnormalities in close-circuit television (CCTV) footage using statistical models of low-level motion features. In this paper we specifically address the problem of estimating the running quantile of a data stream with non-stationary stochasticity when the memory for storing observations is limited. We make several major contributions: (i) we derive an important theoretical result which shows that the change in the quantile of a stream is constrained regardless of the stochastic properties of data, (ii) we describe a set of high-level design goals for an effective estimation algorithm that emerge as a consequence of our theoretical findings, (iii) we introduce a novel algorithm which implements the aforementioned design goals by retaining a sample of data values in a manner adaptive to changes in the distribution of data and progressively narrowing down its focus in the periods of quasi-stationary stochasticity, and (iv) we present a comprehensive evaluation of the proposed algorithm and compare it with the existing methods in the literature on both synthetic data sets and three large `real-world' streams acquired in the course of operation of an existing commercial surveillance system. Our findings convincingly demonstrate that the proposed method is highly successful and vastly outperforms the existing alternatives, especially when the target quantile is high valued and the available buffer capacity severely limited.

##### Abstract (translated by Google)
估计分布的特定分位数的需要是在许多计算机视觉和信号处理应用中经常出现的重要问题。例如，我们的工作受到许多半自动监视分析系统的要求的启发，这些半自动监视分析系统使用低层运动特征的统计模型来检测闭路电视（CCTV）镜头中的异常。在本文中，我们具体地解决了当存储器用于存储观测值有限时估计具有非平稳随机性的数据流的运行分位数的问题。我们做出了几个主要的贡献：（i）我们得到一个重要的理论结果，表明一个流的分位数的变化受到约束，而不管数据的随机性，（ii）我们描述了一组高层次的设计目标一个有效的估计算法，作为我们的理论发现的结果出现，（iii）我们引入一种新的算法，实现上述设计目标，保留一个数据值的样本适应数据分布的变化和逐步缩小（iv）我们对所提出的算法进行综合评估，并将其与现有文献中关于合成数据集和三个大型“真实世界”数据流的方法进行比较现有商业监控系统的运作过程。我们的研究结果令人信服地证明，所提出的方法是非常成功的，并且远远优于现有的替代方法，特别是当目标分位数被高估并且可用缓冲容量严重受限时。

##### URL
[https://arxiv.org/abs/1504.05302](https://arxiv.org/abs/1504.05302)

##### PDF
[https://arxiv.org/pdf/1504.05302](https://arxiv.org/pdf/1504.05302)

