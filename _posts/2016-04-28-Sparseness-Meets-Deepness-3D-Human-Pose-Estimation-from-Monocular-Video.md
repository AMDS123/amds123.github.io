---
layout: post
title: "Sparseness Meets Deepness: 3D Human Pose Estimation from Monocular Video"
date: 2016-04-28 14:53:43
categories: arXiv_CV
tags: arXiv_CV Sparse Pose_Estimation CNN Inference
author: Xiaowei Zhou, Menglong Zhu, Spyridon Leonardos, Kosta Derpanis, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the challenge of 3D full-body human pose estimation from a monocular image sequence. Here, two cases are considered: (i) the image locations of the human joints are provided and (ii) the image locations of joints are unknown. In the former case, a novel approach is introduced that integrates a sparsity-driven 3D geometric prior and temporal smoothness. In the latter case, the former case is extended by treating the image locations of the joints as latent variables. A deep fully convolutional network is trained to predict the uncertainty maps of the 2D joint locations. The 3D pose estimates are realized via an Expectation-Maximization algorithm over the entire sequence, where it is shown that the 2D joint location uncertainties can be conveniently marginalized out during inference. Empirical evaluation on the Human3.6M dataset shows that the proposed approaches achieve greater 3D pose estimation accuracy over state-of-the-art baselines. Further, the proposed approach outperforms a publicly available 2D pose estimation baseline on the challenging PennAction dataset.

##### Abstract (translated by Google)
本文从单眼图像序列中解决了3D全身人体姿态估计的挑战。这里考虑两种情况：（i）提供人体关节的图像位置，（ii）关节的图像位置未知。在前一种情况下，引入了一种新颖的方法，该方法集成了稀疏驱动的3D几何先验和时间平滑。在后一种情况下，通过将关节的图像位置作为潜在变量来处理前一种情况。训练深度完全卷积网络来预测2D关节位置的不确定性图。三维姿态估计是通过整个序列上的期望 - 最大化算法来实现的，其中显示了2D关节位置不确定性可以方便地在推理期间被排除在外。对Human3.6M数据集的经验评估表明，所提出的方法比现有基线获得更高的3D姿态估计精度。此外，所提出的方法优于在具有挑战性的PennAction数据集上公开可用的2D姿态估计基线。

##### URL
[https://arxiv.org/abs/1511.09439](https://arxiv.org/abs/1511.09439)

##### PDF
[https://arxiv.org/pdf/1511.09439](https://arxiv.org/pdf/1511.09439)

