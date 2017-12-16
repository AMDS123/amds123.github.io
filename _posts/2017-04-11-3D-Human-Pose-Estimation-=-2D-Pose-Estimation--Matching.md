---
layout: post
title: "3D Human Pose Estimation = 2D Pose Estimation + Matching"
date: 2017-04-11 07:33:51
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction
author: Ching-Hang Chen, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
We explore 3D human pose estimation from a single RGB image. While many approaches try to directly predict 3D pose from image measurements, we explore a simple architecture that reasons through intermediate 2D pose predictions. Our approach is based on two key observations (1) Deep neural nets have revolutionized 2D pose estimation, producing accurate 2D predictions even for poses with self occlusions. (2) Big-data sets of 3D mocap data are now readily available, making it tempting to lift predicted 2D poses to 3D through simple memorization (e.g., nearest neighbors). The resulting architecture is trivial to implement with off-the-shelf 2D pose estimation systems and 3D mocap libraries. Importantly, we demonstrate that such methods outperform almost all state-of-the-art 3D pose estimation systems, most of which directly try to regress 3D pose from 2D measurements.

##### Abstract (translated by Google)
我们从单个RGB图像探索3D人体姿态估计。虽然很多方法试图从图像测量直接预测三维姿态，但我们通过中间二维姿态预测来探索一个简单的体系结构。我们的方法是基于两个关键的观察（1）深度神经网络已经彻底改变了2D姿态估计，甚至对于具有自我遮挡的姿态也能产生准确的2D预测。 （2）现在已经可以容易地获得3D数据捕捉数据的大数据集，使得通过简单记忆（例如，最近邻居）将预测的2D姿势提升到3D是诱人的。由此产生的体系结构对于使用现成的2D姿态估计系统和3D mocap库来说是微不足道的。重要的是，我们证明这样的方法胜过几乎所有最先进的三维姿态估计系统，其中大部分直接尝试从二维测量回归三维姿态。

##### URL
[https://arxiv.org/abs/1612.06524](https://arxiv.org/abs/1612.06524)

##### PDF
[https://arxiv.org/pdf/1612.06524](https://arxiv.org/pdf/1612.06524)

