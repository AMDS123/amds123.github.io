---
layout: post
title: "Understanding Trajectory Behavior: A Motion Pattern Approach"
date: 2015-01-04 00:07:00
categories: arXiv_CV
tags: arXiv_CV GAN
author: Mahdi M. Kalayeh, Stephen Mussmann, Alla Petrakova, Niels da Vitoria Lobo, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Mining the underlying patterns in gigantic and complex data is of great importance to data analysts. In this paper, we propose a motion pattern approach to mine frequent behaviors in trajectory data. Motion patterns, defined by a set of highly similar flow vector groups in a spatial locality, have been shown to be very effective in extracting dominant motion behaviors in video sequences. Inspired by applications and properties of motion patterns, we have designed a framework that successfully solves the general task of trajectory clustering. Our proposed algorithm consists of four phases: flow vector computation, motion component extraction, motion component's reachability set creation, and motion pattern formation. For the first phase, we break down trajectories into flow vectors that indicate instantaneous movements. In the second phase, via a Kmeans clustering approach, we create motion components by clustering the flow vectors with respect to their location and velocity. Next, we create motion components' reachability set in terms of spatial proximity and motion similarity. Finally, for the fourth phase, we cluster motion components using agglomerative clustering with the weighted Jaccard distance between the motion components' signatures, a set created using path reachability. We have evaluated the effectiveness of our proposed method in an extensive set of experiments on diverse datasets. Further, we have shown how our proposed method handles difficulties in the general task of trajectory clustering that challenge the existing state-of-the-art methods.

##### Abstract (translated by Google)
在巨大而复杂的数据中挖掘底层模式对数据分析师来说非常重要。在本文中，我们提出了一种运动模式方法来挖掘轨迹数据中的频繁行为。运动模式由一组空间局部性的高度相似的流向量组定义，已被证明在提取视频序列中的主要运动行为方面非常有效。受运动模式的应用和性质的启发，我们设计了一个成功解决轨迹聚类的一般任务的框架。我们提出的算法由四个阶段组成：流向矢量计算，运动分量提取，运动分量的可达性集创建和运动模式形成。对于第一阶段，我们将轨迹分解成流向量，表示瞬时运动。在第二阶段，通过Kmeans聚类方法，我们通过聚集流向量相对于它们的位置和速度来创建运动分量。接下来，我们根据空间邻近度和运动相似度来创建运动组件的可达性集。最后，对于第四阶段，我们使用凝聚聚类运动组件的运动组件，运动组件签名之间的加权Jaccard距离，使用路径可达性创建一个集合。我们已经在不同的数据集上进行了广泛的实验，评估了我们提出的方法的有效性。此外，我们已经展示了我们提出的方法如何处理弹道聚类的一般任务中的困难，这挑战了现有的最先进的方法。

##### URL
[https://arxiv.org/abs/1501.00614](https://arxiv.org/abs/1501.00614)

##### PDF
[https://arxiv.org/pdf/1501.00614](https://arxiv.org/pdf/1501.00614)

