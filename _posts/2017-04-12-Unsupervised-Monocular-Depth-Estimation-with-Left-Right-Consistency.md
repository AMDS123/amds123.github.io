---
layout: post
title: "Unsupervised Monocular Depth Estimation with Left-Right Consistency"
date: 2017-04-12 14:40:50
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Clément Godard, Oisin Mac Aodha, Gabriel J. Brostow
mathjax: true
---

* content
{:toc}

##### Abstract
Learning based methods have shown very promising results for the task of depth estimation in single images. However, most existing approaches treat depth prediction as a supervised regression problem and as a result, require vast quantities of corresponding ground truth depth data for training. Just recording quality depth data in a range of environments is a challenging problem. In this paper, we innovate beyond existing approaches, replacing the use of explicit depth data during training with easier-to-obtain binocular stereo footage. We propose a novel training objective that enables our convolutional neural network to learn to perform single image depth estimation, despite the absence of ground truth depth data. Exploiting epipolar geometry constraints, we generate disparity images by training our network with an image reconstruction loss. We show that solving for image reconstruction alone results in poor quality depth images. To overcome this problem, we propose a novel training loss that enforces consistency between the disparities produced relative to both the left and right images, leading to improved performance and robustness compared to existing approaches. Our method produces state of the art results for monocular depth estimation on the KITTI driving dataset, even outperforming supervised methods that have been trained with ground truth depth.

##### Abstract (translated by Google)
基于学习的方法对于单幅图像中的深度估计的任务已经显示出非常有希望的结果。然而，大多数现有方法将深度预测视为监督回归问题，因此需要大量相应的地面真实深度数据进行训练。只是在一系列环境中记录质量深度数据是一个具有挑战性的问题。在本文中，我们创新超越了现有的方法，取代了在训练过程中使用明确的深度数据和更容易获取的双眼立体画面。我们提出了一个新的训练目标，使我们的卷积神经网络学习执行单一的图像深度估计，尽管没有地面真实深度数据。利用极线几何约束，我们通过训练我们的网络图像重构损失来生成视差图像。我们表明，单独解决图像重建会导致质量较差的深度图像。为了克服这个问题，我们提出了一个新的训练损失，强化相对于左和右图像产生的差异之间的一致性，导致与现有方法相比改进的性能和鲁棒性。我们的方法可以在KITTI驾驶数据集上进行单眼深度估算，甚至超越已经用地面真实深度训练的监督方法。

##### URL
[https://arxiv.org/abs/1609.03677](https://arxiv.org/abs/1609.03677)

##### PDF
[https://arxiv.org/pdf/1609.03677](https://arxiv.org/pdf/1609.03677)

