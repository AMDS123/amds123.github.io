---
layout: post
title: "Hand Pose Estimation through Semi-Supervised and Weakly-Supervised Learning"
date: 2017-09-15 09:24:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation
author: Natalia Neverova, Christian Wolf, Florian Nebout, Graham Taylor
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for hand pose estimation based on a deep regressor trained on two different kinds of input. Raw depth data is fused with an intermediate representation in the form of a segmentation of the hand into parts. This intermediate representation contains important topological information and provides useful cues for reasoning about joint locations. The mapping from raw depth to segmentation maps is learned in a semi/weakly-supervised way from two different datasets: (i) a synthetic dataset created through a rendering pipeline including densely labeled ground truth (pixelwise segmentations); and (ii) a dataset with real images for which ground truth joint positions are available, but not dense segmentations. Loss for training on real images is generated from a patch-wise restoration process, which aligns tentative segmentation maps with a large dictionary of synthetic poses. The underlying premise is that the domain shift between synthetic and real data is smaller in the intermediate representation, where labels carry geometric and topological meaning, than in the raw input domain. Experiments on the NYU dataset show that the proposed training method decreases error on joints over direct regression of joints from depth data by 15.7%.

##### Abstract (translated by Google)
我们提出了一种基于两种不同输入训练的深度回归器的手势估计方法。原始深度数据以手的分割形式与中间表示融合为多个部分。这个中间表示包含重要的拓扑信息，并提供有用的线索推理联合地点。从原始深度到分割图的映射是通过半/弱监督的方式从两个不同的数据集中学习的：（i）通过渲染流水线创建的合成数据集，包括密集标记的地面实况（按像素分段）;和（ii）具有真实图像的数据集，其中地面真实关节位置可用，但不是密集的分割。真实图像的训练损失是从补丁方式的恢复过程中产生的，它将暂定的分割图与一个合成姿势的大字典对齐。潜在的前提是合成数据和真实数据之间的域转换在中间表示中比在原始输入域中更小，其中标签具有几何和拓扑的含义。在纽约大学数据集上的实验表明，所提出的训练方法减少了关节从深度数据直接回归的误差15.7％。

##### URL
[https://arxiv.org/abs/1511.06728](https://arxiv.org/abs/1511.06728)

##### PDF
[https://arxiv.org/pdf/1511.06728](https://arxiv.org/pdf/1511.06728)

