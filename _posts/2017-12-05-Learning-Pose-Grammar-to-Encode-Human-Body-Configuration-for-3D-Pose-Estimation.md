---
layout: post
title: "Learning Pose Grammar to Encode Human Body Configuration for 3D Pose Estimation"
date: 2017-12-05 08:49:06
categories: arXiv_CV
tags: arXiv_CV Knowledge Pose_Estimation RNN
author: Haoshu Fang, Yuanlu Xu, Wenguan Wang, Xiaobai Liu, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a pose grammar to tackle the problem of 3D human pose estimation. Our model directly takes 2D pose as input and learns a generalized 2D-3D mapping function. The proposed model consists of a base network which efficiently captures pose-aligned features and a hierarchy of Bi-directional RNNs (BRNN) on the top to explicitly incorporate a set of knowledge regarding human body configuration (i.e., kinematics, symmetry, motor coordination). The proposed model thus enforces high-level constraints over human poses. In learning, we develop a pose sample simulator to augment training samples in virtual camera views, which further improves our model generalizability. We validate our method on public 3D human pose benchmarks and propose a new evaluation protocol working on cross-view setting to verify the generalization capability of different methods. We empirically observe that most state-of-the-art methods encounter difficulty under such setting while our method can well handle such challenges.

##### Abstract (translated by Google)
在本文中，我们提出了姿态语法来解决三维人体姿态估计问题。我们的模型直接将2D姿态作为输入，学习一个广义的2D-3D映射函数。所提出的模型由一个基础网络组成，该基础网络能够高效地捕获顶部的姿态对齐特征和双向RNN（BRNN）的层次结构，以明确地包含关于人体配置（即，运动学，对称性，运动协调） 。所提出的模型因此对人的姿势施加高水平的限制。在学习中，我们开发了一个姿势样本模拟器来增强虚拟相机视图中的训练样本，这进一步提高了我们的模型的普遍性。我们验证了我们的公共三维人体姿态基准方法，并提出了一个新的评估协议，在交叉视图设置工作，以验证不同方法的泛化能力。我们凭经验观察到大多数最先进的方法在这样的环境下遇到困难，而我们的方法可以很好地处理这样的挑战。

##### URL
[http://arxiv.org/abs/1710.06513](http://arxiv.org/abs/1710.06513)

##### PDF
[http://arxiv.org/pdf/1710.06513](http://arxiv.org/pdf/1710.06513)

