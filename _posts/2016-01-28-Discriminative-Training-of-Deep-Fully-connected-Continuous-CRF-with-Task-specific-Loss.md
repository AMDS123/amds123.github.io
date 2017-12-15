---
layout: post
title: "Discriminative Training of Deep Fully-connected Continuous CRF with Task-specific Loss"
date: 2016-01-28 05:30:50
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference Classification Prediction
author: Fayao Liu, Guosheng Lin, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Recent works on deep conditional random fields (CRF) have set new records on many vision tasks involving structured predictions. Here we propose a fully-connected deep continuous CRF model for both discrete and continuous labelling problems. We exemplify the usefulness of the proposed model on multi-class semantic labelling (discrete) and the robust depth estimation (continuous) problems. In our framework, we model both the unary and the pairwise potential functions as deep convolutional neural networks (CNN), which are jointly learned in an end-to-end fashion. The proposed method possesses the main advantage of continuously-valued CRF, which is a closed-form solution for the Maximum a posteriori (MAP) inference. To better adapt to different tasks, instead of using the commonly employed maximum likelihood CRF parameter learning protocol, we propose task-specific loss functions for learning the CRF parameters. It enables direct optimization of the quality of the MAP estimates during the course of learning. Specifically, we optimize the multi-class classification loss for the semantic labelling task and the Turkey's biweight loss for the robust depth estimation problem. Experimental results on the semantic labelling and robust depth estimation tasks demonstrate that the proposed method compare favorably against both baseline and state-of-the-art methods. In particular, we show that although the proposed deep CRF model is continuously valued, with the equipment of task-specific loss, it achieves impressive results even on discrete labelling tasks.

##### Abstract (translated by Google)
近期有关深度条件随机场（CRF）的研究为许多涉及结构化预测的视觉任务设定了新的记录。在这里，我们提出了一个完全连接的深度连续CRF模型，用于离散和连续标签问题。我们举例说明了多类语义标注（离散）模型和稳健深度估计（连续）问题的有用性。在我们的框架中，我们将一元和二元潜在函数建模为深度卷积神经网络（CNN），它们是以端到端的方式共同学习的。该方法具有连续值CRF的主要优点，它是一种最大后验概率（MAP）推断的闭式解。为了更好地适应不同的任务，我们提出了用于学习CRF参数的任务特定损失函数，而不是使用常用的最大似然CRF参数学习协议。它可以在学习过程中直接优化MAP估计的质量。具体而言，我们针对鲁棒深度估计问题优化了语义标记任务的多类分类损失和土耳其的生物权重损失。对语义标注和稳健深度估计任务的实验结果表明，所提出的方法与基线和最先进的方法相比是有利的。具体而言，我们表明，尽管提出的深CRF模型是连续的价值，具有任务特定损失的设备，即使在离散标记任务上也取得了令人印象深刻的结果。

##### URL
[https://arxiv.org/abs/1601.07649](https://arxiv.org/abs/1601.07649)

##### PDF
[https://arxiv.org/pdf/1601.07649](https://arxiv.org/pdf/1601.07649)

