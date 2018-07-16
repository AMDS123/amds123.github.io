---
layout: post
title: "CTAP: Complementary Temporal Action Proposal Generation"
date: 2018-07-12 21:07:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Jiyang Gao, Kan Chen, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal action proposal generation is an important task, akin to object proposals, temporal action proposals are intended to capture "clips" or temporal intervals in videos that are likely to contain an action. Previous methods can be divided to two groups: sliding window ranking and actionness score grouping. Sliding windows uniformly cover all segments in videos, but the temporal boundaries are imprecise; grouping based method may have more precise boundaries but it may omit some proposals when the quality of actionness score is low. Based on the complementary characteristics of these two methods, we propose a novel Complementary Temporal Action Proposal (CTAP) generator. Specifically, we apply a Proposal-level Actionness Trustworthiness Estimator (PATE) on the sliding windows proposals to generate the probabilities indicating whether the actions can be correctly detected by actionness scores, the windows with high scores are collected. The collected sliding windows and actionness proposals are then processed by a temporal convolutional neural network for proposal ranking and boundary adjustment. CTAP outperforms state-of-the-art methods on average recall (AR) by a large margin on THUMOS-14 and ActivityNet 1.3 datasets. We further apply CTAP as a proposal generation method in an existing action detector, and show consistent significant improvements.

##### Abstract (translated by Google)
时间动作提议生成是一项重要任务，类似于对象提议，时间动作提议旨在捕获可能包含动作的视频中的“剪辑”或时间间隔。以前的方法可以分为两组：滑动窗口排名和操作性分数分组。滑动窗口统一覆盖视频中的所有片段，但时间边界不精确;基于分组的方法可以具有更精确的边界，但是当行动质量得分的质量低时，它可以省略一些提议。基于这两种方法的互补特征，我们提出了一种新的补充时间行动建议（CTAP）发生器。具体地，我们在滑动窗口提议上应用提议级别动作可信度估计器（PATE）以生成指示动作是否可以通过动作性分数正确检测到的概率，收集具有高分数的窗口。然后，通过时间卷积神经网络处理所收集的滑动窗口和动作性提议，以用于提议排序和边界调整。 CTAP在THUMOS-14和ActivityNet 1.3数据集上的表现优于平均召回（AR）的最新方法。我们进一步将CTAP用作现有动作检测器中的提议生成方法，并显示出一致的显着改进。

##### URL
[http://arxiv.org/abs/1807.04821](http://arxiv.org/abs/1807.04821)

##### PDF
[http://arxiv.org/pdf/1807.04821](http://arxiv.org/pdf/1807.04821)

