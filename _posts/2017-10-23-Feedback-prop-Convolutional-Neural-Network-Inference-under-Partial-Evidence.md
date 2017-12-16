---
layout: post
title: "Feedback-prop: Convolutional Neural Network Inference under Partial Evidence"
date: 2017-10-23 00:29:49
categories: arXiv_CV
tags: arXiv_CV CNN Inference Prediction Recognition
author: Tianlu Wang, Kota Yamaguchi, Vicente Ordonez
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an inference procedure for deep convolutional neural networks (CNNs) where partial evidence might be available during inference. We introduce a general feedback-based propagation approach (feedback-prop) that allows us to boost the prediction accuracy of an existing CNN model for an arbitrary set of unknown image labels when a non-overlapping arbitrary set of labels is known. We show that existing models trained in a multi-label or multi-task setting can readily take advantage of feedback-prop without any retraining or fine-tuning. This inference procedure also enables us to evaluate empirically various CNN architectures for the intermediate layers with the most information sharing with respect to target outputs. Our feedback-prop inference procedure is general, simple, reliable, and works on different challenging visual recognition tasks. We present two variants of feedback-prop based on layer-wise, and residual iterative updates. We peform evaluations in several tasks involving multiple simultaneous predictions and show that feedback-prop is effective in all of them. In summary, our experiments show a previously unreported and interesting dynamic property of deep CNNs, and presents a technical approach that takes advantage of this property for inference under partial evidence for general visual recognition tasks.

##### Abstract (translated by Google)
在本文中，我们提出了深度卷积神经网络（CNNs）的推理过程，推理过程中可能有部分证据可用。我们引入一种基于反馈的一般性传播方法（feedback-prop），当一个非重叠的任意一组标签被知道时，我们可以提高现有CNN模型对任意一组未知图像标签的预测精度。我们展示了在多标签或多任务设置下训练的现有模型可以容易地利用反馈支撑，而无需任何再训练或微调。这个推理过程也使我们能够根据经验对各种中间层的CNN架构进行经验性的评估，并在目标输出方面共享最多的信息。我们的反馈支持推理程序是一般的，简单的，可靠的，适用于不同的具有挑战性的视觉识别任务。我们提出了基于分层的反馈支持和残差迭代更新的两种变体。我们对涉及多个同时预测的若干任务进行评估，并显示反馈支持对所有这些都是有效的。总之，我们的实验显示了一个以前未被报道和有趣的深层CNN的动态属性，并提出了一种技术途径，利用这个属性在部分证据推理下进行一般的视觉识别任务。

##### URL
[https://arxiv.org/abs/1710.08049](https://arxiv.org/abs/1710.08049)

##### PDF
[https://arxiv.org/pdf/1710.08049](https://arxiv.org/pdf/1710.08049)

