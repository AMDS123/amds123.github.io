---
layout: post
title: "Incremental Loop Closure Verification by Guided Sampling"
date: 2015-09-25 07:49:50
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Detection SLAM
author: Kanji Tanaka
mathjax: true
---

* content
{:toc}

##### Abstract
Loop closure detection, the task of identifying locations revisited by a robot in a sequence of odometry and perceptual observations, is typically formulated as a combination of two subtasks: (1) bag-of-words image retrieval and (2) post-verification using RANSAC geometric verification. The main contribution of this study is the proposal of a novel post-verification framework that achieves good precision recall trade-off in loop closure detection. This study is motivated by the fact that not all loop closure hypotheses are equally plausible (e.g., owing to mutual consistency between loop closure constraints) and that if we have evidence that one hypothesis is more plausible than the others, then it should be verified more frequently. We demonstrate that the problem of loop closure detection can be viewed as an instance of a multi-model hypothesize-and-verify framework and build guided sampling strategies on the framework where loop closures proposed using image retrieval are verified in a planned order (rather than in a conventional uniform order) to operate in a constant time. Experimental results using a stereo SLAM system confirm that the proposed strategy, the use of loop closure constraints and robot trajectory hypotheses as a guide, achieves promising results despite the fact that there exists a significant number of false positive constraints and hypotheses.

##### Abstract (translated by Google)
环路闭合检测，识别由机器人在测距和感知观察序列中重新访问的位置的任务通常被表述为两个子任务的组合：（1）字袋图像检索和（2）使用后验证RANSAC几何验证。本研究的主要贡献在于提出了一种新颖的验证后验框架，在回路闭合检测中实现了良好的精度召回权衡。这项研究的动机是，并非所有的闭环假设都是同样合理的（例如，由于环路闭合约束之间的相互一致性），并且如果我们有证据表明一个假设比其他假设更合理，那么应该验证更多经常。我们证明，闭环检测的问题可以被看作是一个多模型假设和验证框架的实例，并且在框架中建立引导抽样策略，其中使用图像检索提出的闭环封闭按照计划的顺序被验证（而不是以传统的统一顺序）以恒定的时间运行。使用立体声SLAM系统的实验结果证实，尽管事实上存在大量的假阳性约束和假设，但所提出的策略（使用环路闭合约束和机器人轨迹假设作为指导）实现了有希望的结果。

##### URL
[https://arxiv.org/abs/1509.07611](https://arxiv.org/abs/1509.07611)

##### PDF
[https://arxiv.org/pdf/1509.07611](https://arxiv.org/pdf/1509.07611)

