---
layout: post
title: "Harvesting Multiple Views for Marker-less 3D Human Pose Annotations"
date: 2017-04-16 16:19:19
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Georgios Pavlakos, Xiaowei Zhou, Konstantinos G. Derpanis, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances with Convolutional Networks (ConvNets) have shifted the bottleneck for many computer vision tasks to annotated data collection. In this paper, we present a geometry-driven approach to automatically collect annotations for human pose prediction tasks. Starting from a generic ConvNet for 2D human pose, and assuming a multi-view setup, we describe an automatic way to collect accurate 3D human pose annotations. We capitalize on constraints offered by the 3D geometry of the camera setup and the 3D structure of the human body to probabilistically combine per view 2D ConvNet predictions into a globally optimal 3D pose. This 3D pose is used as the basis for harvesting annotations. The benefit of the annotations produced automatically with our approach is demonstrated in two challenging settings: (i) fine-tuning a generic ConvNet-based 2D pose predictor to capture the discriminative aspects of a subject's appearance (i.e.,"personalization"), and (ii) training a ConvNet from scratch for single view 3D human pose prediction without leveraging 3D pose groundtruth. The proposed multi-view pose estimator achieves state-of-the-art results on standard benchmarks, demonstrating the effectiveness of our method in exploiting the available multi-view information.

##### Abstract (translated by Google)
卷积网络（ConvNets）的最新进展已经将许多计算机视觉任务的瓶颈转移到了注释数据收集上。在本文中，我们提出了一种几何驱动的方法来自动收集人体姿态预测任务的注释。从用于2D人体姿势的通用ConvNet开始，并假设多视图设置，我们描述了一种自动方式来收集准确的3D人体姿势注释。我们利用由相机设置的3D几何和人体的3D结构提供的约束来将每个视图2D ConvNet预测概率性地组合成全局最优的3D姿态。这个3D姿势被用作收集注释的基础。我们的方法自动产生的注释的好处在两个具有挑战性的设置中被证明：（i）微调基于ConvNet的二维姿势预测器以捕捉对象外观的区别性方面（即“个性化”）和ii）从零开始训练ConvNet以用于单视图3D人体姿势预测而不利用3D姿势groundtruth。所提出的多视角姿态估计器在标准基准上实现了最新的结果，证明了我们的方法在利用可用的多视图信息方面的有效性。

##### URL
[https://arxiv.org/abs/1704.04793](https://arxiv.org/abs/1704.04793)

##### PDF
[https://arxiv.org/pdf/1704.04793](https://arxiv.org/pdf/1704.04793)

