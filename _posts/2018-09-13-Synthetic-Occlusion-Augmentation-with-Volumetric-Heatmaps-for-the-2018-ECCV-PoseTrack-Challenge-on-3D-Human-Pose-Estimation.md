---
layout: post
title: "Synthetic Occlusion Augmentation with Volumetric Heatmaps for the 2018 ECCV PoseTrack Challenge on 3D Human Pose Estimation"
date: 2018-09-13 14:27:15
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Prediction
author: Istv&#xe1;n S&#xe1;r&#xe1;ndi, Timm Linder, Kai O. Arras, Bastian Leibe
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present our winning entry at the 2018 ECCV PoseTrack Challenge on 3D human pose estimation. Using a fully-convolutional backbone architecture, we obtain volumetric heatmaps per body joint, which we convert to coordinates using soft-argmax. Absolute person center depth is estimated by a 1D heatmap prediction head. The coordinates are back-projected to 3D camera space, where we minimize the L1 loss. Key to our good results is the training data augmentation with randomly placed occluders from the Pascal VOC dataset. In addition to reaching first place in the Challenge, our method also surpasses the state-of-the-art on the full Human3.6M benchmark among methods that use no additional pose datasets in training.

##### Abstract (translated by Google)
在本文中，我们将介绍我们在2018年ECCV PoseTrack挑战赛中获得的关于3D人体姿态估计的获奖作品。使用完全卷积骨架结构，我们获得每个身体关节的体积热图，我们使用soft-argmax将其转换为坐标。绝对人中心深度由1D热图预测头估计。坐标被反投影到3D相机空间，在那里我们最小化L1损失。我们良好结果的关键是使用来自Pascal VOC数据集的随机放置的遮挡物进行训练数据增强。除了在挑战赛中获得第一名之外，我们的方法在训练中不使用额外姿势数据集的方法中也超过了完整的Human3.6M基准测试的最新技术水平。

##### URL
[http://arxiv.org/abs/1809.04987](http://arxiv.org/abs/1809.04987)

##### PDF
[http://arxiv.org/pdf/1809.04987](http://arxiv.org/pdf/1809.04987)

