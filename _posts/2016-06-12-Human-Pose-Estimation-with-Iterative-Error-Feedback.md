---
layout: post
title: "Human Pose Estimation with Iterative Error Feedback"
date: 2016-06-12 19:10:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation CNN Classification Prediction
author: Joao Carreira, Pulkit Agrawal, Katerina Fragkiadaki, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
Hierarchical feature extractors such as Convolutional Networks (ConvNets) have achieved impressive performance on a variety of classification tasks using purely feedforward processing. Feedforward architectures can learn rich representations of the input space but do not explicitly model dependencies in the output spaces, that are quite structured for tasks such as articulated human pose estimation or object segmentation. Here we propose a framework that expands the expressive power of hierarchical feature extractors to encompass both input and output spaces, by introducing top-down feedback. Instead of directly predicting the outputs in one go, we use a self-correcting model that progressively changes an initial solution by feeding back error predictions, in a process we call Iterative Error Feedback (IEF). IEF shows excellent performance on the task of articulated pose estimation in the challenging MPII and LSP benchmarks, matching the state-of-the-art without requiring ground truth scale annotation.

##### Abstract (translated by Google)
诸如卷积网络（ConvNet）的分层特征提取器已经在使用纯前馈处理的各种分类任务上取得了令人印象深刻的性能。前馈架构可以学习输入空间的丰富表示，但并不明确地建模输出空间中的依赖关系，这些依赖关系对于诸如关节式人体姿态估计或对象分割等任务而言是相当结构化的。在这里我们提出了一个框架，通过引入自顶向下的反馈，扩展了分层特征提取器的输入和输出空间的表达能力。我们不是一次直接预测输出，而是使用一个自我校正模型，通过反馈错误预测逐步改变初始解，在我们称为迭代错误反馈（IEF）的过程中。在具有挑战性的MPII和LSP基准测试中，IEF显示出优异的性能表现，能够在不需要基本真实尺度注释的情况下匹配最新技术。

##### URL
[https://arxiv.org/abs/1507.06550](https://arxiv.org/abs/1507.06550)

##### PDF
[https://arxiv.org/pdf/1507.06550](https://arxiv.org/pdf/1507.06550)

