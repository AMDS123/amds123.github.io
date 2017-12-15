---
layout: post
title: "Cascade Learning by Optimally Partitioning"
date: 2015-08-18 14:12:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: Yanwei Pang, Jiale Cao, Xuelong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Cascaded AdaBoost classifier is a well-known efficient object detection algorithm. The cascade structure has many parameters to be determined. Most of existing cascade learning algorithms are designed by assigning detection rate and false positive rate to each stage either dynamically or statically. Their objective functions are not directly related to minimum computation cost. These algorithms are not guaranteed to have optimal solution in the sense of minimizing computation cost. On the assumption that a strong classifier is given, in this paper we propose an optimal cascade learning algorithm (we call it iCascade) which iteratively partitions the strong classifiers into two parts until predefined number of stages are generated. iCascade searches the optimal number ri of weak classifiers of each stage i by directly minimizing the computation cost of the cascade. Theorems are provided to guarantee the existence of the unique optimal solution. Theorems are also given for the proposed efficient algorithm of searching optimal parameters ri. Once a new stage is added, the parameter ri for each stage decreases gradually as iteration proceeds, which we call decreasing phenomenon. Moreover, with the goal of minimizing computation cost, we develop an effective algorithm for setting the optimal threshold of each stage classifier. In addition, we prove in theory why more new weak classifiers are required compared to the last stage. Experimental results on face detection demonstrate the effectiveness and efficiency of the proposed algorithm.

##### Abstract (translated by Google)
级联的AdaBoost分类器是一种众所周知的高效物体检测算法。级联结构有很多参数需要确定。大多数现有的级联学习算法是通过动态或静态地为每个阶段分配检测率和误报率来设计的。其目标函数与最小计算成本没有直接关系。从最小化计算成本的角度来看，这些算法不能保证有最佳的解决方案。在给出强分类器的假设下，本文提出了一种最优级联学习算法（我们称之为iCascade），它将强分类器迭代地分成两部分，直到产生预定数量的阶段。 iCascade通过直接最小化级联的计算代价来搜索每个阶段i的弱分类器的最优数量ri。定理提供了保证独特的最优解的存在。提出了求解最优参数ri的有效算法的定理。一旦增加一个新的阶段，随着迭代的进行，每个阶段的参数ri逐渐减小，我们称之为减少现象。此外，为了最小化计算成本，我们开发了一个有效的算法来设置每个阶段分类器的最佳阈值。另外，我们从理论上证明为什么与最后阶段相比，需要更多新的弱分类器。人脸检测的实验结果表明了该算法的有效性和有效性。

##### URL
[https://arxiv.org/abs/1508.04326](https://arxiv.org/abs/1508.04326)

##### PDF
[https://arxiv.org/pdf/1508.04326](https://arxiv.org/pdf/1508.04326)

