---
layout: post
title: "Borrowing Treasures from the Wealthy: Deep Transfer Learning through Selective Joint Fine-tuning"
date: 2017-06-06 11:51:03
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Classification Deep_Learning
author: Weifeng Ge, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks require a large amount of labeled training data during supervised learning. However, collecting and labeling so much data might be infeasible in many cases. In this paper, we introduce a source-target selective joint fine-tuning scheme for improving the performance of deep learning tasks with insufficient training data. In this scheme, a target learning task with insufficient training data is carried out simultaneously with another source learning task with abundant training data. However, the source learning task does not use all existing training data. Our core idea is to identify and use a subset of training images from the original source learning task whose low-level characteristics are similar to those from the target learning task, and jointly fine-tune shared convolutional layers for both tasks. Specifically, we compute descriptors from linear or nonlinear filter bank responses on training images from both tasks, and use such descriptors to search for a desired subset of training samples for the source learning task. Experiments demonstrate that our selective joint fine-tuning scheme achieves state-of-the-art performance on multiple visual classification tasks with insufficient training data for deep learning. Such tasks include Caltech 256, MIT Indoor 67, Oxford Flowers 102 and Stanford Dogs 120. In comparison to fine-tuning without a source domain, the proposed method can improve the classification accuracy by 2% - 10% using a single model.

##### Abstract (translated by Google)
深度神经网络在监督学习期间需要大量标记的训练数据。然而，在很多情况下，收集和标注这么多的数据可能是不可行的。在本文中，我们引入一个源 - 目标选择性联合微调方案来提高训练数据不足的深度学习任务的性能。在该方案中，训练数据不足的目标学习任务与训练数据丰富的另一个源学习任务同时进行。但是，源学习任务不使用所有现有的培训数据。我们的核心思想是从原始源学习任务中识别和使用与目标学习任务相似的低级特征的训练图像子集，共同调整共享卷积层。具体而言，我们根据来自两个任务的训练图像的线性或非线性滤波器组响应来计算描述符，并且使用这样的描述符来搜索用于源学习任务的期望的训练样本子集。实验证明，我们的选择性联合微调方案在多种视觉分类任务上达到了最佳性能，而深度学习的训练数据不足。这些任务包括加州理工学院256，麻省理工学院室内67，牛津花102和斯坦福大学的狗120.与没有源域微调相比，该方法可以提高2％-10％的分类准确率使用单一模型。

##### URL
[https://arxiv.org/abs/1702.08690](https://arxiv.org/abs/1702.08690)

##### PDF
[https://arxiv.org/pdf/1702.08690](https://arxiv.org/pdf/1702.08690)

