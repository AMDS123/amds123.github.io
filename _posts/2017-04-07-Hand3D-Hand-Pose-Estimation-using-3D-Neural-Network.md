---
layout: post
title: "Hand3D: Hand Pose Estimation using 3D Neural Network"
date: 2017-04-07 13:27:48
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Xiaoming Deng, Shuo Yang, Yinda Zhang, Ping Tan, Liang Chang, Hongan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel 3D neural network architecture for 3D hand pose estimation from a single depth image. Different from previous works that mostly run on 2D depth image domain and require intermediate or post process to bring in the supervision from 3D space, we convert the depth map to a 3D volumetric representation, and feed it into a 3D convolutional neural network(CNN) to directly produce the pose in 3D requiring no further process. Our system does not require the ground truth reference point for initialization, and our network architecture naturally integrates both local feature and global context in 3D space. To increase the coverage of the hand pose space of the training data, we render synthetic depth image by transferring hand pose from existing real image datasets. We evaluation our algorithm on two public benchmarks and achieve the state-of-the-art performance. The synthetic hand pose dataset will be available.

##### Abstract (translated by Google)
我们提出了一个新的三维神经网络架构的3D手姿态估计从一个单一的深度图像。与之前大多运行在二维深度图像领域的工作不同，我们将深度图转化为三维体积表示，并将其输入到三维卷积神经网络（CNN）中，直接在3D中产生姿势，不需要进一步的处理。我们的系统不需要地面参考点进行初始化，我们的网络架构在3D空间中自然地集成了局部特征和全局上下文。为了增加训练数据的手部姿态空间的覆盖范围，我们通过从现有的真实图像数据集转移手部姿态来渲染合成的深度图像。我们在两个公共基准评估我们的算法，并达到最先进的性能。合成的手形数据集将可用。

##### URL
[https://arxiv.org/abs/1704.02224](https://arxiv.org/abs/1704.02224)

##### PDF
[https://arxiv.org/pdf/1704.02224](https://arxiv.org/pdf/1704.02224)

