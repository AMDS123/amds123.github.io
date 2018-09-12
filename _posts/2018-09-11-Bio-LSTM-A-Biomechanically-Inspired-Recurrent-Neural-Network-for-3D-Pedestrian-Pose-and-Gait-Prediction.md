---
layout: post
title: "Bio-LSTM: A Biomechanically Inspired Recurrent Neural Network for 3D Pedestrian Pose and Gait Prediction"
date: 2018-09-11 07:11:32
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Xiaoxiao Du, Ram Vasudevan, Matthew Johnson-Roberson
mathjax: true
---

* content
{:toc}

##### Abstract
In applications such as autonomous driving, it is important to understand, infer, and anticipate the intention and future behavior of pedestrians. This ability allows vehicles to avoid collisions and improve ride safety and quality. This paper proposes a biomechanically inspired recurrent neural network (Bio-LSTM) that can predict the location and 3D articulated body pose of pedestrians in a global coordinate frame, given 3D poses and locations estimated in prior frames with inaccuracy. The proposed network is able to predict poses and global locations for multiple pedestrians simultaneously, for pedestrians up to 45 meters from the cameras (urban intersection scale). The outputs of the proposed network are full-body 3D meshes represented in Skinned Multi-Person Linear (SMPL) model parameters. The proposed approach relies on a novel objective function that incorporates the periodicity of human walking (gait), the mirror symmetry of the human body, and the change of ground reaction forces in a human gait cycle. This paper presents prediction results on the PedX dataset, a large-scale, in-the-wild data set collected at real urban intersections with heavy pedestrian traffic. Results show that the proposed network can successfully learn the characteristics of pedestrian gait and produce accurate and consistent 3D pose predictions.

##### Abstract (translated by Google)
在自动驾驶等应用中，了解，推断和预测行人的意图和未来行为非常重要。这种能力允许车辆避免碰撞并提高乘坐安全性和质量。本文提出了一种生物力学启发的递归神经网络（Bio-LSTM），可以预测全球坐标系中行人的位置和三维关节体姿态，给出三维姿态和在先前帧中估计的位置不准确。所提出的网络能够同时预测多个行人的姿势和全球位置，对于距离摄像机最远45米的行人（城市交叉口规模）。所提出的网络的输出是在蒙皮多人线性（SMPL）模型参数中表示的全身3D网格。所提出的方法依赖于新的目标函数，其结合了人类行走的周期性（步态），人体的镜像对称性以及人类步态周期中地面反作用力的变化。本文介绍了PedX数据集的预测结果，这是一个在人行交通繁忙的实际城市交叉口收集的大规模野外数据集。结果表明，所提出的网络能够成功地学习行人步态的特征，并产生准确一致的三维姿态预测。

##### URL
[http://arxiv.org/abs/1809.03705](http://arxiv.org/abs/1809.03705)

##### PDF
[http://arxiv.org/pdf/1809.03705](http://arxiv.org/pdf/1809.03705)

