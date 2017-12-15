---
layout: post
title: "Unsupervised Network Pretraining via Encoding Human Design"
date: 2016-01-22 23:49:28
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Recognition
author: Ming-Yu Liu, Arun Mallya, Oncel C. Tuzel, Xi Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Over the years, computer vision researchers have spent an immense amount of effort on designing image features for the visual object recognition task. We propose to incorporate this valuable experience to guide the task of training deep neural networks. Our idea is to pretrain the network through the task of replicating the process of hand-designed feature extraction. By learning to replicate the process, the neural network integrates previous research knowledge and learns to model visual objects in a way similar to the hand-designed features. In the succeeding finetuning step, it further learns object-specific representations from labeled data and this boosts its classification power. We pretrain two convolutional neural networks where one replicates the process of histogram of oriented gradients feature extraction, and the other replicates the process of region covariance feature extraction. After finetuning, we achieve substantially better performance than the baseline methods.

##### Abstract (translated by Google)
多年来，计算机视觉研究人员花费了大量的精力来为视觉对象识别任务设计图像特征。我们建议把这个宝贵的经验用来指导训练深度神经网络的任务。我们的想法是通过复制手动设计特征提取过程的任务来预训网络。通过学习复制过程，神经网络将以前的研究知识集成起来，并以类似于手工设计的特征的方式学习模拟可视对象。在接下来的微调步骤中，它从标记的数据中进一步学习对象特定的表示，并且这提高了它的分类能力。我们预先编制了两个卷积神经网络，其中一个复制了面向梯度特征提取的直方图过程，另一个复制了区域协方差特征提取过程。微调之后，我们比基准方法获得了更好的性能。

##### URL
[https://arxiv.org/abs/1502.05689](https://arxiv.org/abs/1502.05689)

##### PDF
[https://arxiv.org/pdf/1502.05689](https://arxiv.org/pdf/1502.05689)

