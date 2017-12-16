---
layout: post
title: "Obstacle Avoidance through Deep Networks based Intermediate Perception"
date: 2017-04-27 21:55:07
categories: arXiv_CV
tags: arXiv_CV Face CNN Prediction
author: Shichao Yang, Sandeep Konam, Chen Ma, Stephanie Rosenthal, Manuela Veloso, Sebastian Scherer
mathjax: true
---

* content
{:toc}

##### Abstract
Obstacle avoidance from monocular images is a challenging problem for robots. Though multi-view structure-from-motion could build 3D maps, it is not robust in textureless environments. Some learning based methods exploit human demonstration to predict a steering command directly from a single image. However, this method is usually biased towards certain tasks or demonstration scenarios and also biased by human understanding. In this paper, we propose a new method to predict a trajectory from images. We train our system on more diverse NYUv2 dataset. The ground truth trajectory is computed from the designed cost functions automatically. The Convolutional Neural Network perception is divided into two stages: first, predict depth map and surface normal from RGB images, which are two important geometric properties related to 3D obstacle representation. Second, predict the trajectory from the depth and normal. Results show that our intermediate perception increases the accuracy by 20% than the direct prediction. Our model generalizes well to other public indoor datasets and is also demonstrated for robot flights in simulation and experiments.

##### Abstract (translated by Google)
单眼图像的障碍避免对机器人来说是一个挑战性的问题。尽管多视点运动结构可以构建3D地图，但在无纹理的环境中却不够健壮。一些基于学习的方法利用人类示范来直接从单个图像预测转向命令。然而，这种方法通常偏向于某些任务或示范场景，并且也被人们的理解所左右。在本文中，我们提出了一种从图像预测轨迹的新方法。我们训练我们的系统更多样化的NYUv2数据集。地面实况轨迹由设计的成本函数自动计算。卷积神经网络感知分为两个阶段：首先，从RGB图像预测深度图和表面法线，这是与三维障碍物表示相关的两个重要的几何性质。其次，从深度和正常预测轨迹。结果表明，我们的中间感知比直接预测提高了20％的准确性。我们的模型很好地适用于其他公共室内数据集，并且在仿真和实验中也演示了机器人飞行。

##### URL
[https://arxiv.org/abs/1704.08759](https://arxiv.org/abs/1704.08759)

##### PDF
[https://arxiv.org/pdf/1704.08759](https://arxiv.org/pdf/1704.08759)

