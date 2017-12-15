---
layout: post
title: "Searching Action Proposals via Spatial Actionness Estimation and Temporal Path Inference and Tracking"
date: 2016-08-23 13:08:30
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization Inference Detection
author: Nannan Li, Dan Xu, Zhenqiang Ying, Zhihao Li, Ge Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of searching action proposals in unconstrained video clips. Our approach starts from actionness estimation on frame-level bounding boxes, and then aggregates the bounding boxes belonging to the same actor across frames via linking, associating, tracking to generate spatial-temporal continuous action paths. To achieve the target, a novel actionness estimation method is firstly proposed by utilizing both human appearance and motion cues. Then, the association of the action paths is formulated as a maximum set coverage problem with the results of actionness estimation as a priori. To further promote the performance, we design an improved optimization objective for the problem and provide a greedy search algorithm to solve it. Finally, a tracking-by-detection scheme is designed to further refine the searched action paths. Extensive experiments on two challenging datasets, UCF-Sports and UCF-101, show that the proposed approach advances state-of-the-art proposal generation performance in terms of both accuracy and proposal quantity.

##### Abstract (translated by Google)
在本文中，我们解决了在无约束的视频剪辑中搜索行动建议的问题。我们的方法从帧级边界框的动作估计开始，然后通过链接，关联，跟踪来聚合属于相同演员的边界框，以产生时空连续的动作路径。为了达到这个目标，首先提出了一种利用人的外观和运动线索的新颖的动作估计方法。然后，行为路径的关联被表述为以行为估计的结果为先验的最大集合覆盖问题。为了进一步提高性能，我们设计了一个改进的问题优化目标，并提供了一个贪婪的搜索算法来解决它。最后，设计一种逐行检测方案来进一步优化搜索到的行为路径。在UCF-Sports和UCF-101这两个具有挑战性的数据集上进行的大量实验表明，所提出的方法在准确性和提案数量方面都提高了最新的提案生成性能。

##### URL
[https://arxiv.org/abs/1608.06495](https://arxiv.org/abs/1608.06495)

##### PDF
[https://arxiv.org/pdf/1608.06495](https://arxiv.org/pdf/1608.06495)

