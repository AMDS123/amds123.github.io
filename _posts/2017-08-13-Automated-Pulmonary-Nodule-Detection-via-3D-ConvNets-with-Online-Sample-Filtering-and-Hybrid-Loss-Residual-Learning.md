---
layout: post
title: "Automated Pulmonary Nodule Detection via 3D ConvNets with Online Sample Filtering and Hybrid-Loss Residual Learning"
date: 2017-08-13 07:33:55
categories: arXiv_CV
tags: arXiv_CV CNN Detection Recognition
author: Qi Dou, Hao Chen, Yueming Jin, Huangjing Lin, Jing Qin, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel framework with 3D convolutional networks (ConvNets) for automated detection of pulmonary nodules from low-dose CT scans, which is a challenging yet crucial task for lung cancer early diagnosis and treatment. Different from previous standard ConvNets, we try to tackle the severe hard/easy sample imbalance problem in medical datasets and explore the benefits of localized annotations to regularize the learning, and hence boost the performance of ConvNets to achieve more accurate detections. Our proposed framework consists of two stages: 1) candidate screening, and 2) false positive reduction. In the first stage, we establish a 3D fully convolutional network, effectively trained with an online sample filtering scheme, to sensitively and rapidly screen the nodule candidates. In the second stage, we design a hybrid-loss residual network which harnesses the location and size information as important cues to guide the nodule recognition procedure. Experimental results on the public large-scale LUNA16 dataset demonstrate superior performance of our proposed method compared with state-of-the-art approaches for the pulmonary nodule detection task.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的三维卷积网络框架（ConvNets），用于从低剂量CT扫描中自动检测肺结节，这对于肺癌的早期诊断和治疗来说是一个具有挑战性但至关重要的任务。不同于以往的标准通信网络，我们试图解决医疗数据集中严重的/简单的样本不平衡问题，并探讨本地化注释对学习的正规化的好处，从而提高ConvNets的性能，实现更准确的检测。我们提出的框架包括两个阶段：1）候选人筛选，2）假阳性减少。在第一阶段，我们建立了一个三维完全卷积网络，通过在线样本过滤方案进行有效训练，以灵敏快速地筛选结节候选者。在第二阶段，我们设计一个混合损失的残留网络，利用位置和大小信息作为重要线索来指导结节识别过程。在公共大型LUNA16数据集上的实验结果证明了我们提出的方法与肺结节检测任务的现有技术方法相比的优越性能。

##### URL
[https://arxiv.org/abs/1708.03867](https://arxiv.org/abs/1708.03867)

##### PDF
[https://arxiv.org/pdf/1708.03867](https://arxiv.org/pdf/1708.03867)

