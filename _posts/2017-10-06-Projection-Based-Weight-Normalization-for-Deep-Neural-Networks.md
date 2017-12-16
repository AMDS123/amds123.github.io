---
layout: post
title: "Projection Based Weight Normalization for Deep Neural Networks"
date: 2017-10-06 10:24:38
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Optimization
author: Lei Huang, Xianglong Liu, Bo Lang, Bo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Optimizing deep neural networks (DNNs) often suffers from the ill-conditioned problem. We observe that the scaling-based weight space symmetry property in rectified nonlinear network will cause this negative effect. Therefore, we propose to constrain the incoming weights of each neuron to be unit-norm, which is formulated as an optimization problem over Oblique manifold. A simple yet efficient method referred to as projection based weight normalization (PBWN) is also developed to solve this problem. PBWN executes standard gradient updates, followed by projecting the updated weight back to Oblique manifold. This proposed method has the property of regularization and collaborates well with the commonly used batch normalization technique. We conduct comprehensive experiments on several widely-used image datasets including CIFAR-10, CIFAR-100, SVHN and ImageNet for supervised learning over the state-of-the-art convolutional neural networks, such as Inception, VGG and residual networks. The results show that our method is able to improve the performance of DNNs with different architectures consistently. We also apply our method to Ladder network for semi-supervised learning on permutation invariant MNIST dataset, and our method outperforms the state-of-the-art methods: we obtain test errors as 2.52%, 1.06%, and 0.91% with only 20, 50, and 100 labeled samples, respectively.

##### Abstract (translated by Google)
优化深度神经网络（DNN）经常遭受病态问题。我们观察到在整流后的非线性网络中基于尺度的权重空间对称性会造成这种负面影响。因此，我们建议将每个神经元的权值约束为单位范数，这是在斜流形上形成的一个优化问题。为了解决这个问题，还开发了一种简单而有效的称为基于投影的权重归一化（PBWN）的方法。 PBWN执行标准梯度更新，然后将更新的权重投影回斜角流形。该方法具有正则化的性质，与常用的批量归一化技术相配合。我们在几个广泛使用的图像数据集（包括CIFAR-10，CIFAR-100，SVHN和ImageNet）上进行了全面的实验，用于监督学习最先进的卷积神经网络，如Inception，VGG和残留网络。结果表明，我们的方法能够一致地改进不同体系结构的DNN的性能。我们还将该方法应用于梯形网络，用于置换不变MNIST数据集上的半监督学习，我们的方法优于最先进的方法：测试误差分别为2.52％，1.06％和0.91％，只有20 ，50和100个标记的样本。

##### URL
[https://arxiv.org/abs/1710.02338](https://arxiv.org/abs/1710.02338)

##### PDF
[https://arxiv.org/pdf/1710.02338](https://arxiv.org/pdf/1710.02338)

