---
layout: post
title: "A Framework for Human Pose Estimation in Videos"
date: 2016-04-26 18:45:25
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization
author: Dong Zhang, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a method to estimate a sequence of human poses in unconstrained videos. We aim to demonstrate that by using temporal information, the human pose estimation results can be improved over image based pose estimation methods. In contrast to the commonly employed graph optimization formulation, which is NP-hard and needs approximate solutions, we formulate this problem into a unified two stage tree-based optimization problem for which an efficient and exact solution exists. Although the proposed method finds an exact solution, it does not sacrifice the ability to model the spatial and temporal constraints between body parts in the frames; in fact it models the {\em symmetric} parts better than the existing methods. The proposed method is based on two main ideas: `Abstraction' and `Association' to enforce the intra- and inter-frame body part constraints without inducing extra computational complexity to the polynomial time solution. Using the idea of `Abstraction', a new concept of `abstract body part' is introduced to conceptually combine the symmetric body parts and model them in the tree based body part structure. Using the idea of `Association', the optimal tracklets are generated for each abstract body part, in order to enforce the spatiotemporal constraints between body parts in adjacent frames. A sequence of the best poses is inferred from the abstract body part tracklets through the tree-based optimization. Finally, the poses are refined by limb alignment and refinement schemes. We evaluated the proposed method on three publicly available video based human pose estimation datasets, and obtained dramatically improved performance compared to the state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出一种方法来估计无约束视频中的人体姿势序列。我们的目的是通过使用时间信息来展示人脸姿态估计结果可以在基于图像的姿态估计方法上得到改善。与通常采用的NP-hard并需要近似解的图优化公式相比，我们将这个问题制定成一个统一的两阶段基于树的优化问题，其中存在一个有效且精确的解。虽然所提出的方法找到了一个精确的解决方案，但它不会牺牲模型框架中的身体部位之间的空间和时间约束的能力;实际上它比现有的方法更好地模拟{\ em对称}部分。所提出的方法基于两个主要思想：“抽象”和“关联”来执行帧内和帧间身体部分约束，而不会给多项式时间解决方案带来额外的计算复杂度。采用“抽象”的概念，引入了“抽象身体部位”的概念，在概念上将对称身体部位组合起来，并在基于树体的身体部位结构中进行建模。使用“关联”的思想，为每个抽象的身体部位生成最优的轨迹，以强化相邻框架中身体部位之间的时空约束。通过基于树的优化从抽象的身体部位tracklets推断出最佳姿势的序列。最后，通过肢体对齐和细化方案来改进姿势。我们在三个公开可用的基于视频的人体姿态估计数据集上评估了所提出的方法，并且与现有技术的方法相比，获得了显着改善的性能。

##### URL
[https://arxiv.org/abs/1604.07788](https://arxiv.org/abs/1604.07788)

##### PDF
[https://arxiv.org/pdf/1604.07788](https://arxiv.org/pdf/1604.07788)

