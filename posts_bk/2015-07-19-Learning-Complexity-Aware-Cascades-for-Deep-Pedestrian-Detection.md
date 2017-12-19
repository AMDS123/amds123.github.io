---
layout: post
title: "Learning Complexity-Aware Cascades for Deep Pedestrian Detection"
date: 2015-07-19 22:31:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Optimization Detection
author: Zhaowei Cai, Mohammad Saberian, Nuno Vasconcelos
mathjax: true
---

* content
{:toc}

##### Abstract
The design of complexity-aware cascaded detectors, combining features of very different complexities, is considered. A new cascade design procedure is introduced, by formulating cascade learning as the Lagrangian optimization of a risk that accounts for both accuracy and complexity. A boosting algorithm, denoted as complexity aware cascade training (CompACT), is then derived to solve this optimization. CompACT cascades are shown to seek an optimal trade-off between accuracy and complexity by pushing features of higher complexity to the later cascade stages, where only a few difficult candidate patches remain to be classified. This enables the use of features of vastly different complexities in a single detector. In result, the feature pool can be expanded to features previously impractical for cascade design, such as the responses of a deep convolutional neural network (CNN). This is demonstrated through the design of a pedestrian detector with a pool of features whose complexities span orders of magnitude. The resulting cascade generalizes the combination of a CNN with an object proposal mechanism: rather than a pre-processing stage, CompACT cascades seamlessly integrate CNNs in their stages. This enables state of the art performance on the Caltech and KITTI datasets, at fairly fast speeds.

##### Abstract (translated by Google)
考虑复杂感知级联探测器的设计，结合非常不同复杂性的特征。引入一个新的级联设计程序，通过将级联学习作为拉格朗日风险的优化来考虑准确性和复杂性。然后导出表示为复杂感知级联训练（CompACT）的提升算法以解决该优化。 CompACT级联被证明在精度和复杂度之间寻求最佳的折中，通过将更高复杂度的特性推送到后面的级联级，其中只有少数困难的候选补丁被分类。这使得能够在单个检测器中使用极其不同复杂度的特征。结果，特征池可以扩展到以前不适用于级联设计的特征，例如深度卷积神经网络（CNN）的响应。这通过设计一个具有特征池的行人检测器来证明，其复杂性跨越数量级。由此产生的级联概括了CNN与对象提议机制的结合：而不是一个预处理阶段，CompACT级联将CNN无缝地整合到其阶段中。这使加州理工学院和KITTI数据集的艺术表现能够以相当快的速度进行。

##### URL
[https://arxiv.org/abs/1507.05348](https://arxiv.org/abs/1507.05348)

##### PDF
[https://arxiv.org/pdf/1507.05348](https://arxiv.org/pdf/1507.05348)

