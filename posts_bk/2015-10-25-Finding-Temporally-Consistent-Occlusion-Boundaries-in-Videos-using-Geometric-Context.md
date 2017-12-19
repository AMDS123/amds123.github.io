---
layout: post
title: "Finding Temporally Consistent Occlusion Boundaries in Videos using Geometric Context"
date: 2015-10-25 23:20:38
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: S. Hussain Raza, Ahmad Humayun, Matthias Grundmann, David Anderson, Irfan Essa
mathjax: true
---

* content
{:toc}

##### Abstract
We present an algorithm for finding temporally consistent occlusion boundaries in videos to support segmentation of dynamic scenes. We learn occlusion boundaries in a pairwise Markov random field (MRF) framework. We first estimate the probability of an spatio-temporal edge being an occlusion boundary by using appearance, flow, and geometric features. Next, we enforce occlusion boundary continuity in a MRF model by learning pairwise occlusion probabilities using a random forest. Then, we temporally smooth boundaries to remove temporal inconsistencies in occlusion boundary estimation. Our proposed framework provides an efficient approach for finding temporally consistent occlusion boundaries in video by utilizing causality, redundancy in videos, and semantic layout of the scene. We have developed a dataset with fully annotated ground-truth occlusion boundaries of over 30 videos ($5000 frames). This dataset is used to evaluate temporal occlusion boundaries and provides a much needed baseline for future studies. We perform experiments to demonstrate the role of scene layout, and temporal information for occlusion reasoning in dynamic scenes.

##### Abstract (translated by Google)
我们提出一种算法来寻找视频中时间一致的遮挡边界来支持动态场景的分割。我们学习成对马尔可夫随机场（MRF）框架中的遮挡边界。我们首先通过使用外观，流动和几何特征来估计时空边缘是遮挡边界的概率。接下来，我们通过使用随机森林学习成对遮挡概率来强化MRF模型中的遮挡边界连续性。然后，我们在时间上平滑边界以消除遮挡边界估计中的时间不一致性。我们提出的框架提供了一种有效的方法，通过利用因果关系，视频中的冗余和场景的语义布局来找到视频中时间一致的遮挡边界。我们已经开发了一个数据集，其中包含超过30个视频的完全注释的地面真实遮挡边界（5000帧）。这个数据集被用来评估时间遮挡边界，并为将来的研究提供了一个非常需要的基线。我们进行实验来演示场景布局的作用，以及在动态场景中用于遮挡推理的时间信息。

##### URL
[https://arxiv.org/abs/1510.07323](https://arxiv.org/abs/1510.07323)

##### PDF
[https://arxiv.org/pdf/1510.07323](https://arxiv.org/pdf/1510.07323)

