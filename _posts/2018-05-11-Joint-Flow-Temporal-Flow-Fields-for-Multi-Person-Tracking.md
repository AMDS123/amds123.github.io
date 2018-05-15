---
layout: post
title: "Joint Flow: Temporal Flow Fields for Multi Person Tracking"
date: 2018-05-11 21:27:08
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Tracking Optimization
author: Andreas Doering, Umar Iqbal, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose an online multi person pose tracker which works on two consecutive frames $I_{t-1}$ and $I_t$. The general formulation of our temporal network allows to rely on any multi person pose estimation network as spatial network. From the spatial network we extract image features and pose features for both frames. These features compose as input for our temporal model that predicts Temporal Flow Fields (TFF). These TFF are vector fields which indicate the direction in which body joint is going to move from frame $I_{t-1}$ to frame $I_t$. This novel representation allows to formulate a similarity measure of detected joints. These similarities are used as binary potentials in an bipartite graph optimization problem in order to perform tracking of multiple poses. We show that these TFF can be learned by a relative small CNN network whilst achieving state-of-the-art multi person pose tracking results.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个在线多人姿势跟踪器，它在两个连续帧$ I_ {t-1} $和$ I_t $上工作。我们的时态网络的一般公式允许依赖任何多人姿态估计网络作为空间网络。从空间网络中，我们提取两个帧的图像特征和姿态特征。这些特征构成了预测时间流场（TFF）的时态模型的输入。这些TFF是指示身体关节将从框架$ I_ {t-1} $移动到框架$ I_t $的方向。这种新颖的表示形式允许制定检测到的关节的相似性度量。这些相似性被用作二分图优化问题中的二元势能，以便执行多个姿态的跟踪。我们表明，这些TFF可以通过相对较小的CNN网络学习，同时实现最先进的多人姿态跟踪结果。

##### URL
[https://arxiv.org/abs/1805.04596](https://arxiv.org/abs/1805.04596)

##### PDF
[https://arxiv.org/pdf/1805.04596](https://arxiv.org/pdf/1805.04596)

