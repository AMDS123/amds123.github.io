---
layout: post
title: "Convolutional Pose Machines"
date: 2016-04-12 03:31:53
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Inference Prediction
author: Shih-En Wei, Varun Ramakrishna, Takeo Kanade, Yaser Sheikh
mathjax: true
---

* content
{:toc}

##### Abstract
Pose Machines provide a sequential prediction framework for learning rich implicit spatial models. In this work we show a systematic design for how convolutional networks can be incorporated into the pose machine framework for learning image features and image-dependent spatial models for the task of pose estimation. The contribution of this paper is to implicitly model long-range dependencies between variables in structured prediction tasks such as articulated pose estimation. We achieve this by designing a sequential architecture composed of convolutional networks that directly operate on belief maps from previous stages, producing increasingly refined estimates for part locations, without the need for explicit graphical model-style inference. Our approach addresses the characteristic difficulty of vanishing gradients during training by providing a natural learning objective function that enforces intermediate supervision, thereby replenishing back-propagated gradients and conditioning the learning procedure. We demonstrate state-of-the-art performance and outperform competing methods on standard benchmarks including the MPII, LSP, and FLIC datasets.

##### Abstract (translated by Google)
Pose Machines为学习丰富的隐式空间模型提供了一个顺序预测框架。在这项工作中，我们展示了一个系统的设计，如何卷积网络可以纳入姿态机框架学习图像特征和图像相关空间模型的任务的姿态估计。本文的贡献是隐式地建模结构化预测任务中的变量之间的长期依赖关系，如关节姿态估计。我们通过设计由卷积网络组成的顺序架构来实现这一点，直接在前一阶段的信念映射上运行，为零件位置提供更精确的估计，而不需要明确的图形模型式推理。我们的方法通过提供自然的学习目标函数来强化中间监督，从而补充反向传播的梯度并调整学习过程，从而解决了在训练过程中消除梯度的特征性难题。我们展示了最先进的性能，并在包括MPII，LSP和FLIC数据集在内的标准基准测试中胜出了各种竞争方法。

##### URL
[https://arxiv.org/abs/1602.00134](https://arxiv.org/abs/1602.00134)

##### PDF
[https://arxiv.org/pdf/1602.00134](https://arxiv.org/pdf/1602.00134)

