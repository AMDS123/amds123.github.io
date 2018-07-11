---
layout: post
title: "Efficient Evaluation of the Number of False Alarm Criterion"
date: 2018-07-10 12:37:14
categories: arXiv_CV
tags: arXiv_CV Detection
author: Sylvie Le H&#xe9;garat-Mascle, Emanuel Aldea, Jennifer Vandoni
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a method for computing efficiently the significance of a parametric pattern inside a binary image. On the one hand, a-contrario strategies avoid the user involvement for tuning detection thresholds, and allow one to account fairly for different pattern sizes. On the other hand, a-contrario criteria become intractable when the pattern complexity in terms of parametrization increases. In this work, we introduce a strategy which relies on the use of a cumulative space of reduced dimensionality, derived from the coupling of a classic (Hough) cumulative space with an integral histogram trick. This space allows us to store partial computations which are required by the a-contrario criterion, and to evaluate the significance with a lower computational cost than by following a straightforward approach. The method is illustrated on synthetic examples on patterns with various parametrizations up to five dimensions. In order to demonstrate how to apply this generic concept in a real scenario, we consider a difficult crack detection task in still images, which has been addressed in the literature with various local and global detection strategies. We model cracks as bounded segments, detected by the proposed a-contrario criterion, which allow us to introduce additional spatial constraints based on their relative alignment. On this application, the proposed strategy yields state-of the-art results, and underlines its potential for handling complex pattern detection tasks.

##### Abstract (translated by Google)
本文提出了一种有效计算二进制图像内参数模式的重要性的方法。一方面，相反的策略避免了用户参与调整检测阈值，并允许人们公平地考虑不同的模式大小。另一方面，当参数化方面的模式复杂性增加时，相反的标准变得难以处理。在这项工作中，我们引入了一种策略，该策略依赖于使用经典（Hough）累积空间与积分直方图技巧的耦合而得到的降维的累积空间。该空间允许我们存储a-相反标准所需的部分计算，并且以比通过简单方法更低的计算成本来评估重要性。该方法在关于具有多达五维的各种参数化的图案的合成示例上示出。为了演示如何在真实场景中应用这种通用概念，我们考虑静止图像中的一个困难的裂缝检测任务，这已经在文献中用各种局部和全局检测策略来解决。我们将裂缝建模为有界区段，通过提出的相反标准检测，这允许我们基于它们的相对对齐引入额外的空间约束。在此应用程序中，所提出的策略产生了最先进的结果，并强调了其处理复杂模式检测任务的潜力。

##### URL
[http://arxiv.org/abs/1807.03594](http://arxiv.org/abs/1807.03594)

##### PDF
[http://arxiv.org/pdf/1807.03594](http://arxiv.org/pdf/1807.03594)

