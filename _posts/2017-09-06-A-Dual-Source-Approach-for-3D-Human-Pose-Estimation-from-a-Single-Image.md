---
layout: post
title: "A Dual-Source Approach for 3D Human Pose Estimation from a Single Image"
date: 2017-09-06 13:24:52
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Inference
author: Umar Iqbal, Andreas Doering, Hashim Yasin, Björn Krüger, Andreas Weber, Juergen Gall
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we address the challenging problem of 3D human pose estimation from single images. Recent approaches learn deep neural networks to regress 3D pose directly from images. One major challenge for such methods, however, is the collection of training data. Specifically, collecting large amounts of training data containing unconstrained images annotated with accurate 3D poses is infeasible. We therefore propose to use two independent training sources. The first source consists of accurate 3D motion capture data, and the second source consists of unconstrained images with annotated 2D poses. To integrate both sources, we propose a dual-source approach that combines 2D pose estimation with efficient 3D pose retrieval. To this end, we first convert the motion capture data into a normalized 2D pose space, and separately learn a 2D pose estimation model from the image data. During inference, we estimate the 2D pose and efficiently retrieve the nearest 3D poses. We then jointly estimate a mapping from the 3D pose space to the image and reconstruct the 3D pose. We provide a comprehensive evaluation of the proposed method and experimentally demonstrate the effectiveness of our approach, even when the skeleton structures of the two sources differ substantially.

##### Abstract (translated by Google)
在这项工作中，我们解决了来自单个图像的3D人体姿态估计的挑战性问题。最近的方法学习深度神经网络直接从图像回归3D姿态。这种方法的一个主要挑战是收集训练数据。具体而言，收集大量包含以准确3D姿势注释的无约束图像的训练数据是不可行的。因此，我们建议使用两个独立的培训资源。第一个来源包括准确的三维动作捕捉数据，第二个来源包括带有注释的二维姿势的无约束图像。为了整合这两个来源，我们提出了一种将2D姿态估计与高效3D姿势检索相结合的双源方法。为此，我们首先将运动捕捉数据转换成归一化的二维姿态空间，并从图像数据中分别学习二维姿态估计模型。在推理过程中，我们估计2D姿态并有效检索最近的3D姿势。然后，我们联合估计从3D姿态空间到图像的映射并重建3D姿态。我们对所提出的方法进行了综合评估，并且实验证明了我们的方法的有效性，即使两个源的骨架结构差异很大。

##### URL
[https://arxiv.org/abs/1705.02883](https://arxiv.org/abs/1705.02883)

##### PDF
[https://arxiv.org/pdf/1705.02883](https://arxiv.org/pdf/1705.02883)

