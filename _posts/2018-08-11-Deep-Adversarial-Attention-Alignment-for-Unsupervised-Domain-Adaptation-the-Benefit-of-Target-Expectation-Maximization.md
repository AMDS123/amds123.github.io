---
layout: post
title: "Deep Adversarial Attention Alignment for Unsupervised Domain Adaptation: the Benefit of Target Expectation Maximization"
date: 2018-08-11 16:44:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Attention CNN
author: Guoliang Kang, Liang Zheng, Yan Yan, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we make two contributions to unsupervised domain adaptation (UDA) using the convolutional neural network (CNN). First, our approach transfers knowledge in all the convolutional layers through attention alignment. Most previous methods align high-level representations, e.g., activations of the fully connected (FC) layers. In these methods, however, the convolutional layers which underpin critical low-level domain knowledge cannot be updated directly towards reducing domain discrepancy. Specifically, we assume that the discriminative regions in an image are relatively invariant to image style changes. Based on this assumption, we propose an attention alignment scheme on all the target convolutional layers to uncover the knowledge shared by the source domain. Second, we estimate the posterior label distribution of the unlabeled data for target network training. Previous methods, which iteratively update the pseudo labels by the target network and refine the target network by the updated pseudo labels, are vulnerable to label estimation errors. Instead, our approach uses category distribution to calculate the cross-entropy loss for training, thereby ameliorating the error accumulation of the estimated labels. The two contributions allow our approach to outperform the state-of-the-art methods by +2.6% on the Office-31 dataset.

##### Abstract (translated by Google)
在本文中，我们使用卷积神经网络（CNN）对无监督域自适应（UDA）做出了两个贡献。首先，我们的方法通过注意力对齐来传递所有卷积层中的知识。大多数先前的方法对齐高级表示，例如，完全连接（FC）层的激活。然而，在这些方法中，支持关键低级域知识的卷积层不能直接更新以减少域差异。具体地，我们假设图像中的判别区域对于图像样式的改变是相对不变的。基于此假设，我们在所有目标卷积层上提出了一种注意对齐方案，以揭示源域共享的知识。其次，我们估计目标网络训练的未标记数据的后标签分布。先前的方法（其通过目标网络迭代地更新伪标签并且通过更新的伪标签来细化目标网络）易受标签估计错误的影响。相反，我们的方法使用类别分布来计算训练的交叉熵损失，从而改善估计标签的误差累积。这两项贡献使我们的方法在Office-31数据集上的表现优于最先进的方法+ 2.6％。

##### URL
[http://arxiv.org/abs/1801.10068](http://arxiv.org/abs/1801.10068)

##### PDF
[http://arxiv.org/pdf/1801.10068](http://arxiv.org/pdf/1801.10068)

