---
layout: post
title: "Global Hypothesis Generation for 6D Object Pose Estimation"
date: 2017-01-02 09:09:03
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization
author: Frank Michel, Alexander Kirillov, Eric Brachmann, Alexander Krull, Stefan Gumhold, Bogdan Savchynskyy, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the task of estimating the 6D pose of a known 3D object from a single RGB-D image. Most modern approaches solve this task in three steps: i) Compute local features; ii) Generate a pool of pose-hypotheses; iii) Select and refine a pose from the pool. This work focuses on the second step. While all existing approaches generate the hypotheses pool via local reasoning, e.g. RANSAC or Hough-voting, we are the first to show that global reasoning is beneficial at this stage. In particular, we formulate a novel fully-connected Conditional Random Field (CRF) that outputs a very small number of pose-hypotheses. Despite the potential functions of the CRF being non-Gaussian, we give a new and efficient two-step optimization procedure, with some guarantees for optimality. We utilize our global hypotheses generation procedure to produce results that exceed state-of-the-art for the challenging "Occluded Object Dataset".

##### Abstract (translated by Google)
本文介绍了从单个RGB-D图像估算已知3D对象的6D姿态的任务。大多数现代的方法分三步解决这个任务：i）计算局部特征; ii）产生一组姿态假设; iii）从池中选择并优化姿势。这项工作着重于第二步。虽然所有现有的方法通过本地推理产生假设池， RANSAC或Hough-voting，我们是第一个表明全球推理在这个阶段是有益的。特别是，我们制定了一种新颖的全连接条件随机场（CRF），输出极少数的姿态假设。尽管CRF的潜在功能是非高斯的，我们给出了一个新的和有效的两步优化程序，并保证了最优性。我们利用我们的全球假设生成程序来产生超过具有挑战性的“遮挡对象数据集”的最新技术的结果。

##### URL
[https://arxiv.org/abs/1612.02287](https://arxiv.org/abs/1612.02287)

##### PDF
[https://arxiv.org/pdf/1612.02287](https://arxiv.org/pdf/1612.02287)

