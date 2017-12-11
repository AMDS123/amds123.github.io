---
layout: post
title: "Simultaneous Hand Pose and Skeleton Bone-Lengths Estimation from a Single Depth Image"
date: 2017-12-08 15:25:00
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Deep_Learning
author: Jameel Malik, Ahmed Elhayek, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
Articulated hand pose estimation is a challenging task for human-computer interaction. The state-of-the-art hand pose estimation algorithms work only with one or a few subjects for which they have been calibrated or trained. Particularly, the hybrid methods based on learning followed by model fitting or model based deep learning do not explicitly consider varying hand shapes and sizes. In this work, we introduce a novel hybrid algorithm for estimating the 3D hand pose as well as bone-lengths of the hand skeleton at the same time, from a single depth image. The proposed CNN architecture learns hand pose parameters and scale parameters associated with the bone-lengths simultaneously. Subsequently, a new hybrid forward kinematics layer employs both parameters to estimate 3D joint positions of the hand. For end-to-end training, we combine three public datasets NYU, ICVL and MSRA-2015 in one unified format to achieve large variation in hand shapes and sizes. Among hybrid methods, our method shows improved accuracy over the state-of-the-art on the combined dataset and the ICVL dataset that contain multiple subjects. Also, our algorithm is demonstrated to work well with unseen images.

##### Abstract (translated by Google)
铰接式手势估计是人机交互的一项具有挑战性的任务。最先进的手姿态估计算法仅适用于一个或几个被校准或训练过的对象。特别地，基于学习的混合方法随后是模型拟合或基于模型的深度学习，不明确地考虑变化的手形和尺寸。在这项工作中，我们引入了一种新的混合算法，用于从单个深度图像同时估计3D手部姿态以及手部骨架的骨骼长度。所提出的CNN架构同时学习了手部姿态参数和与骨骼长度相关的缩放参数。随后，新的混合正向运动学层使用两个参数来估计手的3D关节位置。对于端到端培训，我们将三个公共数据集NYU，ICVL和MSRA-2015以统一的格式结合在一起，以实现手形和大小的巨大变化。在混合方法中，我们的方法比组合数据集和包含多个主题的ICVL数据集在现有技术上显示出改进的准确性。此外，我们的算法被证明与未看到的图像很好地工作。

##### URL
[http://arxiv.org/abs/1712.03121](http://arxiv.org/abs/1712.03121)

##### PDF
[http://arxiv.org/pdf/1712.03121](http://arxiv.org/pdf/1712.03121)

