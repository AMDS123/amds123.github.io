---
layout: post
title: "Crowd Counting Considering Network Flow Constraints in Videos"
date: 2017-12-15 14:22:55
categories: arXiv_CV
tags: arXiv_CV Prediction Relation
author: Liqing Gao, Yanzhang Wang, Xin Ye, Jian Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The growth of the number of people in the monitoring scene may increase the probability of security threat, which makes crowd counting more and more important. Most of the existing approaches estimate the number of pedestrians within one frame, which results in inconsistent predictions in terms of time. This paper, for the first time, introduces a quadratic programming model with the network flow constraints to improve the accuracy of crowd counting. Firstly, the foreground of each frame is segmented into groups, each of which contains several pedestrians. Then, a regression-based map is developed in accordance with the relationship between low-level features of each group and the number of people in it. Secondly, a directed graph is constructed to simulate constraints on people's flow, whose vertices represent groups of each frame and arcs represent people moving from one group to another. Then, the people flow can be viewed as an integer flow in the constructed digraph. Finally, by solving a quadratic programming problem with network flow constraints in the directed graph, we obtain consistency in people counting. The experimental results show that the proposed method can reduce the crowd counting errors and improve the accuracy. Moreover, this method can also be applied to any ultramodern group-based regression counting approach to get improvements.

##### Abstract (translated by Google)
监测场景中人数的增长可能会增加安全威胁的可能性，这使得人群数量越来越重要。现有的大多数方法都是在一帧内估计行人的数量，从而导致在时间上的预测不一致。本文首次引入了具有网络流量约束的二次规划模型，提高了人群统计的准确性。首先，每帧的前景被分割成组，每组包含几个行人。然后，根据每个组的低级特征与其中的人数之间的关系，开发基于回归的地图。其次，构造一个有向图来模拟人流的约束条件，其顶点代表了每一帧的组合，弧则代表从一组到另一组的人。那么，在构造的有向图中，人流可以看作是一个整数流。最后，通过求解有向图中的网络流约束的二次规划问题，我们得到了人数统计的一致性。实验结果表明，该方法可以减少人群统计误差，提高精度。此外，这种方法也可以应用于任何基于超现代群体的回归计数方法来获得改进。

##### URL
[http://arxiv.org/abs/1605.03821](http://arxiv.org/abs/1605.03821)

##### PDF
[http://arxiv.org/pdf/1605.03821](http://arxiv.org/pdf/1605.03821)

