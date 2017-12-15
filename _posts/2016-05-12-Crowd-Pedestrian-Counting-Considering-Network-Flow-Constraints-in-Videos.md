---
layout: post
title: "Crowd Pedestrian Counting Considering Network Flow Constraints in Videos"
date: 2016-05-12 14:12:21
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Liqing Gao, Yanzhang Wang, Xin Ye, Jian Wang
mathjax: true
---

* content
{:toc}

##### Abstract
A quadratic programming method with network flow constraints is proposed to improve crowd pedestrian counting in video surveillance. Most of the existing approaches estimate the number of pedestrians within one frame, which result in inconsistent predictions in temporal domain. In this paper, firstly, we segment the foreground of each frame into different groups, each of which contains several pedestrians. Then we train a regression-based map from low level features of each group to its person number. Secondly, we construct a directed graph to simulate people flow, whose vertices represent groups of each frame and edges represent people moving from one group to another. Then, the people flow can be viewed as an integer flow in the constructed directed graph. Finally, by solving a quadratic programming problem with network flow constraints in the directed graph, we obtain a consistent pedestrian counting. The experimental results show that our method can improve the crowd counting accuracy significantly.

##### Abstract (translated by Google)
提出了一种网络流量约束的二次规划方法来改善视频监控中的人群行人数。现有的大多数方法估计一帧内行人的数量，导致时间域的预测不一致。本文首先将每个帧的前景分成不同的组，每个组包含几个行人。然后我们训练一个从每个组的低级特征到它的人数的基于回归的地图。其次，构造一个有向图来模拟人流，其顶点代表每一帧的组，边代表人们从一组到另一组。然后，在构造的有向图中可以将人流看作一个整数流。最后，通过求解有向图中的网络流约束的二次规划问题，可以得到一致的行人计数。实验结果表明，该方法能显着提高人群的计数精度。

##### URL
[https://arxiv.org/abs/1605.03821](https://arxiv.org/abs/1605.03821)

##### PDF
[https://arxiv.org/pdf/1605.03821](https://arxiv.org/pdf/1605.03821)

