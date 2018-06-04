---
layout: post
title: "MONET: Multiview Semi-supervised Keypoint via Epipolar Divergence"
date: 2018-05-31 21:27:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Yasamin Jafarian, Yuan Yao, Hyun Soo Park
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents MONET---an end-to-end semi-supervised learning framework for a pose detector using multiview image streams. What differentiates MONET from existing models is its capability of detecting general subjects including non-human species without a pre-trained model. A key challenge of such subjects lies in the limited availability of expert manual annotations, which often leads to a large bias in the detection model. We address this challenge by using the epipolar constraint embedded in the unlabeled data in two ways. First, given a set of the labeled data, the keypoint trajectories can be reliably reconstructed in 3D using multiview optical flows, resulting in considerable data augmentation in space and time from nearly exhaustive views. Second, the detection across views must geometrically agree with each other. We introduce a new measure of geometric consistency in keypoint distributions called epipolar divergence---a generalized distance from the epipolar lines to the corresponding keypoint distribution. Epipolar divergence characterizes when two view keypoint distributions produces zero reprojection error. We design a twin network that minimizes the epipolar divergence through stereo rectification that can significantly alleviate computational complexity and sampling aliasing in training. We demonstrate that our framework can localize customized keypoints of diverse species, e.g., humans, dogs, and monkeys.

##### Abstract (translated by Google)
本文介绍了MONET--一种使用多视图图像流的姿态检测器的端到端半监督学习框架。 MONET与现有模型的不同之处在于它能够在没有预先训练的模型的情况下检测一般主题，包括非人类物种。这些主题的关键挑战在于专家手动注释的有限可用性，这经常导致检测模型中的大偏差。我们通过以两种方式使用嵌入在未标记数据中的极线约束来解决这个挑战。首先，给定一组标记的数据，可以使用多视图光流在3D中可靠地重建关键点轨迹，从几乎穷举的视图导致空间和时间上可观的数据增强。其次，跨视点的检测必须在几何上彼此一致。我们在关键点分布中引入了一种新的几何一致性度量，称为极向散度---从极线到对应关键点分布的广义距离。当两个视点关键点分布产生零重投影误差时，极面分歧是特征。我们设计了一个双胞胎网络，通过立体校正将极线分歧降到最低，可显着减轻训练中的计算复杂度和采样混叠。我们证明我们的框架可以定位不同物种的定制关键点，例如人类，狗和猴子。

##### URL
[http://arxiv.org/abs/1806.00104](http://arxiv.org/abs/1806.00104)

##### PDF
[http://arxiv.org/pdf/1806.00104](http://arxiv.org/pdf/1806.00104)

