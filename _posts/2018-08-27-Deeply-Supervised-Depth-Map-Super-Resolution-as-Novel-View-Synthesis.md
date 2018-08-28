---
layout: post
title: "Deeply Supervised Depth Map Super-Resolution as Novel View Synthesis"
date: 2018-08-27 04:54:13
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Xibin Song, Yuchao Dai, Xueying Qin
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural network (DCNN) has been successfully applied to depth map super-resolution and outperforms existing methods by a wide margin. However, there still exist two major issues with these DCNN based depth map super-resolution methods that hinder the performance: i) The low-resolution depth maps either need to be up-sampled before feeding into the network or substantial deconvolution has to be used; and ii) The supervision (high-resolution depth maps) is only applied at the end of the network, thus it is difficult to handle large up-sampling factors, such as $\times 8, \times 16$. In this paper, we propose a new framework to tackle the above problems. First, we propose to represent the task of depth map super-resolution as a series of novel view synthesis sub-tasks. The novel view synthesis sub-task aims at generating (synthesizing) a depth map from different camera pose, which could be learned in parallel. Second, to handle large up-sampling factors, we present a deeply supervised network structure to enforce strong supervision in each stage of the network. Third, a multi-scale fusion strategy is proposed to effectively exploit the feature maps at different scales and handle the blocking effect. In this way, our proposed framework could deal with challenging depth map super-resolution efficiently under large up-sampling factors (e.g. $\times 8, \times 16$). Our method only uses the low-resolution depth map as input, and the support of color image is not needed, which greatly reduces the restriction of our method. Extensive experiments on various benchmarking datasets demonstrate the superiority of our method over current state-of-the-art depth map super-resolution methods.

##### Abstract (translated by Google)
深度卷积神经网络（DCNN）已经成功应用于深度图超分辨率，并且大大优于现有方法。然而，这些基于DCNN的深度图超分辨率方法仍然存在两个主要问题，这些方法阻碍了性能：i）低分辨率深度图要么在馈入网络之前需要进行上采样，要么必须使用大量的去卷积; ii）监督（高分辨率深度图）仅应用于网络末端，因此难以处理大的上采样因子，例如$ \ times 8，\ times 16 $。在本文中，我们提出了一个新的框架来解决上述问题。首先，我们提出将深度图超分辨率的任务表示为一系列新颖的视图合成子任务。新颖视图合成子任务旨在从不同的相机姿势生成（合成）深度图，其可以并行学习。其次，为了处理大量的上采样因素，我们提出了一个深度监督的网络结构，以在网络的每个阶段实施强有力的监督。第三，提出了一种多尺度融合策略，有效地利用不同尺度的特征图，处理阻塞效应。通过这种方式，我们提出的框架可以在大的上采样因子下有效地处理具有挑战性的深度图超分辨率（例如$ \ times 8，\ times 16 $）。我们的方法只使用低分辨率深度图作为输入，不需要彩色图像的支持，大大减少了我们方法的限制。各种基准测试数据集的大量实验证明了我们的方法优于当前最先进的深度图超分辨率方法的优越性。

##### URL
[http://arxiv.org/abs/1808.08688](http://arxiv.org/abs/1808.08688)

##### PDF
[http://arxiv.org/pdf/1808.08688](http://arxiv.org/pdf/1808.08688)

