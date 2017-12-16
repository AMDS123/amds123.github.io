---
layout: post
title: "Coarse-to-Fine Volumetric Prediction for Single-Image 3D Human Pose"
date: 2017-07-26 12:10:16
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Optimization Prediction
author: Georgios Pavlakos, Xiaowei Zhou, Konstantinos G. Derpanis, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the challenge of 3D human pose estimation from a single color image. Despite the general success of the end-to-end learning paradigm, top performing approaches employ a two-step solution consisting of a Convolutional Network (ConvNet) for 2D joint localization and a subsequent optimization step to recover 3D pose. In this paper, we identify the representation of 3D pose as a critical issue with current ConvNet approaches and make two important contributions towards validating the value of end-to-end learning for this task. First, we propose a fine discretization of the 3D space around the subject and train a ConvNet to predict per voxel likelihoods for each joint. This creates a natural representation for 3D pose and greatly improves performance over the direct regression of joint coordinates. Second, to further improve upon initial estimates, we employ a coarse-to-fine prediction scheme. This step addresses the large dimensionality increase and enables iterative refinement and repeated processing of the image features. The proposed approach outperforms all state-of-the-art methods on standard benchmarks achieving a relative error reduction greater than 30% on average. Additionally, we investigate using our volumetric representation in a related architecture which is suboptimal compared to our end-to-end approach, but is of practical interest, since it enables training when no image with corresponding 3D groundtruth is available, and allows us to present compelling results for in-the-wild images.

##### Abstract (translated by Google)
本文从单一的彩色图像解决了三维人体姿态估计的挑战。尽管端到端学习范式取得了普遍的成功，但最佳性能方法采用了由二维联合定位的卷积网络（ConvNet）和后续优化步骤来恢复三维姿态的两步解决方案。在本文中，我们将3D姿态的表示确定为当前ConvNet方法的关键问题，并为验证此任务的端到端学习的价值做出了两个重要贡献。首先，我们提出围绕主题的3D空间的精细离散化，并训练一个ConvNet来预测每个关节的每个体素可能性。这为3D姿态创建了一个自然的表示，并且在关节坐标的直接回归上大大提高了性能。其次，为了进一步改善初步估计，我们采用粗略的预测方案。这一步骤解决了大量的维度增加，并且使图像特征的迭代改进和重复处理成为可能。所提出的方法优于标准基准上的所有最新方法，平均相对误差降低大于30％。另外，我们在相关体系结构中使用体积表示进行了研究，这与我们的端到端方法相比并不理想，但却具有实际意义，因为它能够在没有相应3D地面实体的图像可用时进行训练，并且允许我们在野外图像引人注目的结果。

##### URL
[https://arxiv.org/abs/1611.07828](https://arxiv.org/abs/1611.07828)

##### PDF
[https://arxiv.org/pdf/1611.07828](https://arxiv.org/pdf/1611.07828)

