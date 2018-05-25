---
layout: post
title: "Jointly Optimize Data Augmentation and Network Training: Adversarial Data Augmentation in Human Pose Estimation"
date: 2018-05-24 14:53:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Pose_Estimation
author: Xi Peng, Zhiqiang Tang, Fei Yang, Rogerio Feris, Dimitris Metaxas
mathjax: true
---

* content
{:toc}

##### Abstract
Random data augmentation is a critical technique to avoid overfitting in training deep neural network models. However, data augmentation and network training are usually treated as two isolated processes, limiting the effectiveness of network training. Why not jointly optimize the two? We propose adversarial data augmentation to address this limitation. The main idea is to design an augmentation network (generator) that competes against a target network (discriminator) by generating `hard' augmentation operations online. The augmentation network explores the weaknesses of the target network, while the latter learns from `hard' augmentations to achieve better performance. We also design a reward/penalty strategy for effective joint training. We demonstrate our approach on the problem of human pose estimation and carry out a comprehensive experimental analysis, showing that our method can significantly improve state-of-the-art models without additional data efforts.

##### Abstract (translated by Google)
随机数据增强是避免训练深度神经网络模型过度拟合的关键技术。然而，数据增强和网络培训通常被视为两个孤立的过程，限制了网络培训的有效性。为什么不联合优化这两个？我们提出对抗性数据增强来解决这个限制。主要思想是设计一个增强网络（发生器），通过在线生成“硬”增强操作来与目标网络（鉴别器）竞争。增强网络探索目标网络的弱点，而后者从“硬”增强中学习以获得更好的性能。我们还为有效的联合培训设计奖励/惩罚策略。我们在人体姿态估计问题上展示了我们的方法，并进行了全面的实验分析，表明我们的方法可以显着提高最先进的模型而无需额外的数据工作。

##### URL
[http://arxiv.org/abs/1805.09707](http://arxiv.org/abs/1805.09707)

##### PDF
[http://arxiv.org/pdf/1805.09707](http://arxiv.org/pdf/1805.09707)

