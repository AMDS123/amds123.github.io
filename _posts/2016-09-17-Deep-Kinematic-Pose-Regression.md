---
layout: post
title: "Deep Kinematic Pose Regression"
date: 2016-09-17 11:22:11
categories: arXiv_CV
tags: arXiv_CV Knowledge Pose_Estimation Optimization Gradient_Descent
author: Xingyi Zhou, Xiao Sun, Wei Zhang, Shuang Liang, Yichen Wei
mathjax: true
---

* content
{:toc}

##### Abstract
Learning articulated object pose is inherently difficult because the pose is high dimensional but has many structural constraints. Most existing work do not model such constraints and does not guarantee the geometric validity of their pose estimation, therefore requiring a post-processing to recover the correct geometry if desired, which is cumbersome and sub-optimal. In this work, we propose to directly embed a kinematic object model into the deep neutral network learning for general articulated object pose estimation. The kinematic function is defined on the appropriately parameterized object motion variables. It is differentiable and can be used in the gradient descent based optimization in network training. The prior knowledge on the object geometric model is fully exploited and the structure is guaranteed to be valid. We show convincing experiment results on a toy example and the 3D human pose estimation problem. For the latter we achieve state-of-the-art result on Human3.6M dataset.

##### Abstract (translated by Google)
学习明确的对象姿势本质上是困难的，因为姿势是高维度的，但是具有许多结构约束。大多数现有的工作不能模拟这种约束，并不能保证其姿态估计的几何有效性，因此如果需要，需要后处理来恢复正确的几何形状，这是麻烦的和次优的。在这项工作中，我们建议直接将运动学对象模型嵌入到深度中性网络学习中，用于一般的关节物体姿态估计。运动功能是在适当的参数化对象运动变量上定义的。它是可微分的，可用于网络训练中基于梯度下降的优化。对物体几何模型的先验知识得到充分利用，结构保证有效。我们展示令人信服的实验结果玩具的例子和三维人体姿势估计问题。对于后者，我们在Human3.6M数据集上获得了最新的结果。

##### URL
[https://arxiv.org/abs/1609.05317](https://arxiv.org/abs/1609.05317)

##### PDF
[https://arxiv.org/pdf/1609.05317](https://arxiv.org/pdf/1609.05317)

