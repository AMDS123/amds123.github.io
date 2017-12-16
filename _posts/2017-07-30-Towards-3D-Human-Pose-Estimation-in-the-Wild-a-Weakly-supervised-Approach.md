---
layout: post
title: "Towards 3D Human Pose Estimation in the Wild: a Weakly-supervised Approach"
date: 2017-07-30 15:01:30
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Transfer_Learning Prediction Relation
author: Xingyi Zhou, Qixing Huang, Xiao Sun, Xiangyang Xue, Yichen Wei
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the task of 3D human pose estimation in the wild. This task is challenging due to lack of training data, as existing datasets are either in the wild images with 2D pose or in the lab images with 3D pose. We propose a weakly-supervised transfer learning method that uses mixed 2D and 3D labels in a unified deep neutral network that presents two-stage cascaded structure. Our network augments a state-of-the-art 2D pose estimation sub-network with a 3D depth regression sub-network. Unlike previous two stage approaches that train the two sub-networks sequentially and separately, our training is end-to-end and fully exploits the correlation between the 2D pose and depth estimation sub-tasks. The deep features are better learnt through shared representations. In doing so, the 3D pose labels in controlled lab environments are transferred to in the wild images. In addition, we introduce a 3D geometric constraint to regularize the 3D pose prediction, which is effective in the absence of ground truth depth labels. Our method achieves competitive results on both 2D and 3D benchmarks.

##### Abstract (translated by Google)
在本文中，我们研究了野外三维人体姿态估计的任务。由于缺乏训练数据，这个任务是具有挑战性的，因为现有的数据集要么在2D姿势的野外图像中，要么在3D姿势的实验室图像中。我们提出了一个弱监督的转移学习方法，在统一的深度中性网络中使用混合的二维和三维标签，呈现两级级联结构。我们的网络使用3D深度回归子网络来增强最先进的2D姿态估计子网络。与先前的两个阶段的方法不同，这两个阶段的方法分别对两个子网络进行训练，我们的训练是端到端的，充分利用了二维姿态和深度估计子任务之间的相关性。通过共享表示可以更好地学习深层特征。这样做时，受控实验室环境中的三维姿态标签被转移到野外图像中。另外，我们引入一个三维几何约束来规范三维姿态预测，这是没有地面真实深度标签是有效的。我们的方法在2D和3D基准测试中取得了有竞争力的结果。

##### URL
[https://arxiv.org/abs/1704.02447](https://arxiv.org/abs/1704.02447)

##### PDF
[https://arxiv.org/pdf/1704.02447](https://arxiv.org/pdf/1704.02447)

