---
layout: post
title: "Deep Adversarial Attention Alignment for Unsupervised Domain Adaptation: the Benefit of Target Expectation Maximization"
date: 2018-01-30 15:55:57
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Attention GAN CNN
author: Guoliang Kang, Liang Zheng, Yan Yan, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we make two contributions to unsupervised domain adaptation in the convolutional neural network. First, our approach transfers knowledge in the deep side of neural networks for all convolutional layers. Previous methods usually do so by directly aligning higher-level representations, e.g., aligning the activations of fully-connected layers. In this case, although the convolutional layers can be modified through gradient back-propagation, but not significantly. Our approach takes advantage of the natural image correspondence built by CycleGAN. Departing from previous methods, we use every convolutional layer of the target network to uncover the knowledge shared by the source domain through an attention alignment mechanism. The discriminative part of an image is relatively insensitive to the change of image style, ensuring our attention alignment particularly suitable for robust knowledge adaptation. Second, we estimate the posterior label distribution of the unlabeled data to train the target network. Previous methods, which iteratively update the pseudo labels by the target network and refine the target network by the updated pseudo labels, are straightforward but vulnerable to noisy labels. Instead, our approach uses category distribution to calculate the cross-entropy loss for training, thereby ameliorating deviation accumulation. The two contributions make our approach outperform the state-of-theart methods by +2.6% in all the six transfer tasks on Office- 31 on average. Notably, our approach yields +5.1% improvement for the challenging $\textbf{D}$ ${\rightarrow}$ $\textbf{A}$ task.

##### Abstract (translated by Google)
在本文中，我们对卷积神经网络中的无监督域自适应做出了两个贡献。首先，我们的方法在所有卷积层的神经网络的深层传递知识。以前的方法通常是通过直接对齐更高级的表示来实现的，例如，对齐完全连接的层的激活。在这种情况下，虽然卷积层可以通过梯度反向传播进行修改，但不是很明显。我们的方法利用了CycleGAN构建的自然图像对应。从以前的方法出发，我们使用目标网络的每个卷积层，通过注意对齐机制来揭示源域共享的知识。图像的判别部分对图像风格的变化相对不敏感，确保我们的注意力对齐特别适合于强健的知识适应。其次，我们估计未标记数据的后验标签分布来训练目标网络。先前的方法迭代地更新目标网络的伪标签并通过更新的伪标签精炼目标网络，这些方法是直接的，但易受到噪声标签的影响。相反，我们的方法使用类别分布来计算交叉熵损失的训练，从而改善偏差积累。这两项贡献使我们的办法平均比办公室的六项转拨任务的绩效提高了2.6％。值得注意的是，我们的方法对具有挑战性的$ \ textbf {D} $ {\ rightarrow} $ $ \ textbf {A} $任务产生了+ 5.1％的改进。

##### URL
[http://arxiv.org/abs/1801.10068](http://arxiv.org/abs/1801.10068)

##### PDF
[http://arxiv.org/pdf/1801.10068](http://arxiv.org/pdf/1801.10068)

