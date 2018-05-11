---
layout: post
title: "Learning to Estimate 3D Human Pose and Shape from a Single Color Image"
date: 2018-05-10 17:46:12
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Prediction
author: Georgios Pavlakos, Luyang Zhu, Xiaowei Zhou, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
This work addresses the problem of estimating the full body 3D human pose and shape from a single color image. This is a task where iterative optimization-based solutions have typically prevailed, while Convolutional Networks (ConvNets) have suffered because of the lack of training data and their low resolution 3D predictions. Our work aims to bridge this gap and proposes an efficient and effective direct prediction method based on ConvNets. Central part to our approach is the incorporation of a parametric statistical body shape model (SMPL) within our end-to-end framework. This allows us to get very detailed 3D mesh results, while requiring estimation only of a small number of parameters, making it friendly for direct network prediction. Interestingly, we demonstrate that these parameters can be predicted reliably only from 2D keypoints and masks. These are typical outputs of generic 2D human analysis ConvNets, allowing us to relax the massive requirement that images with 3D shape ground truth are available for training. Simultaneously, by maintaining differentiability, at training time we generate the 3D mesh from the estimated parameters and optimize explicitly for the surface using a 3D per-vertex loss. Finally, a differentiable renderer is employed to project the 3D mesh to the image, which enables further refinement of the network, by optimizing for the consistency of the projection with 2D annotations (i.e., 2D keypoints or masks). The proposed approach outperforms previous baselines on this task and offers an attractive solution for direct prediction of 3D shape from a single color image.

##### Abstract (translated by Google)
这项工作解决了从单一彩色图像估计全身三维人体姿态和形状的问题。这是基于迭代优化的解决方案通常占主导地位的任务，而卷积网络（ConvNets）由于缺乏训练数据和低分辨率3D预测而受到影响。我们的工作旨在填补这一空白，并提出一种基于ConvNets的高效和有效的直接预测方法。我们的方法的中心部分是在我们的端到端框架内引入参数化统计人体形状模型（SMPL）。这使我们能够获得非常详细的三维网格结果，同时仅需要估计少量参数，使其对直接网络预测更为友好。有趣的是，我们证明这些参数只能从2D关键点和掩模中可靠地预测。这些是通用2D人体分析ConvNets的典型输出，使我们能够放松对具有3D形状地面真实性的图像进行训练的巨大需求。同时，通过保持可微性，在训练时间，我们根据估计的参数生成3D网格，并使用3D每顶点损耗为曲面显式优化。最后，采用可微分渲染器来将3D网格投射到图像，这通过优化投影与2D注释（即2D关键点或掩模）的一致性来实现网络的进一步细化。所提出的方法胜过此前任务的基线，并提供了一个有吸引力的解决方案，用于直接从单个彩色图像预测3D形状。

##### URL
[http://arxiv.org/abs/1805.04092](http://arxiv.org/abs/1805.04092)

##### PDF
[http://arxiv.org/pdf/1805.04092](http://arxiv.org/pdf/1805.04092)

