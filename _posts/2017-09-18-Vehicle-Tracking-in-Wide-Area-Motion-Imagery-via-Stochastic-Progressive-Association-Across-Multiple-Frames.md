---
layout: post
title: "Vehicle Tracking in Wide Area Motion Imagery via Stochastic Progressive Association Across Multiple Frames"
date: 2017-09-18 16:40:28
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Ahmed Elliethy, Gaurav Sharma
mathjax: true
---

* content
{:toc}

##### Abstract
Vehicle tracking in Wide Area Motion Imagery (WAMI) relies on associating vehicle detections across multiple WAMI frames to form tracks corresponding to individual vehicles. The temporal window length, i.e., the number $M$ of sequential frames, over which associations are collectively estimated poses a trade-off between accuracy and computational complexity. A larger $M$ improves performance because the increased temporal context enables the use of motion models and allows occlusions and spurious detections to be handled better. The number of total hypotheses tracks, on the other hand, grows exponentially with increasing $M$, making larger values of $M$ computationally challenging to tackle. In this paper, we introduce SPAAM an iterative approach that progressively grows $M$ with each iteration to improve estimated tracks by exploiting the enlarged temporal context while keeping computation manageable through two novel approaches for pruning association hypotheses. First, guided by a road network, accurately co-registered to the WAMI frames, we disregard unlikely associations that do not agree with the road network. Second, as $M$ is progressively enlarged at each iteration, the related increase in association hypotheses is limited by revisiting only the subset of association possibilities rendered open by stochastically determined dis-associations for the previous iteration. The stochastic dis-association at each iteration maintains each estimated association according to an estimated probability for confidence, obtained via a probabilistic model. Associations at each iteration are then estimated globally over the $M$ frames by (approximately) solving a binary integer programming problem for selecting a set of compatible tracks. Vehicle tracking results obtained over test WAMI datasets indicate that our proposed approach provides significant performance improvements over 3 alternatives.

##### Abstract (translated by Google)
广域运动影像（WAMI）中的车辆跟踪依赖于跨越多个WAMI帧的车辆检测以形成对应于各个车辆的轨道。时间窗口长度，即连续帧的数量$ M $，总体上估计的关联构成了精度和计算复杂度之间的折衷。较大的$ M $可以提高性能，因为增加的时间上下文可以使用运动模型，并且可以更好地处理遮挡和虚假检测。另一方面，全部假设跟踪的数量随着$ M $的增加呈指数增长，使得$ M $的较大值在计算上具有挑战性。在本文中，我们介绍SPAAM迭代方法，每次迭代逐步增长$ M $，通过利用扩大的时间上下文来保持计算的可管理性，通过两种新的方法来修剪关联假设来改善估计的轨迹。首先，在道路网络的指导下，准确地与WAMI框架共同注册，我们忽视不太可能与道路网络不一致的关联。其次，由于$ M $在每次迭代中逐渐增大，关联假设的相关增加受到限制，因为只重新审视由前一次迭代随机确定的不相关联而使得所关联的关联可能性的子集。每次迭代的随机分散关联根据通过概率模型获得的估计的置信概率来维护每个估计的关联。然后通过（近似地）解决二进制整数规划问题来选择一组兼容轨道，在每个迭代中的关联在全局$ M $帧上被估计。在测试WAMI数据集上获得的车辆跟踪结果表明，我们提出的方法比3个替代方案提供显着的性能改进。

##### URL
[https://arxiv.org/abs/1709.06035](https://arxiv.org/abs/1709.06035)

##### PDF
[https://arxiv.org/pdf/1709.06035](https://arxiv.org/pdf/1709.06035)

