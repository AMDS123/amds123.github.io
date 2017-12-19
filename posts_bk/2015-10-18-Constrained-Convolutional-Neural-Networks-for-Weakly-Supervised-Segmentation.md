---
layout: post
title: "Constrained Convolutional Neural Networks for Weakly Supervised Segmentation"
date: 2015-10-18 23:51:40
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Optimization Gradient_Descent
author: Deepak Pathak, Philipp Krähenbühl, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to learn a dense pixel-wise labeling from image-level tags. Each image-level tag imposes constraints on the output labeling of a Convolutional Neural Network (CNN) classifier. We propose Constrained CNN (CCNN), a method which uses a novel loss function to optimize for any set of linear constraints on the output space (i.e. predicted label distribution) of a CNN. Our loss formulation is easy to optimize and can be incorporated directly into standard stochastic gradient descent optimization. The key idea is to phrase the training objective as a biconvex optimization for linear models, which we then relax to nonlinear deep networks. Extensive experiments demonstrate the generality of our new learning framework. The constrained loss yields state-of-the-art results on weakly supervised semantic image segmentation. We further demonstrate that adding slightly more supervision can greatly improve the performance of the learning algorithm.

##### Abstract (translated by Google)
我们提出了一种从图像级标签学习密集像素标签的方法。每个图像级标签对卷积神经网络（CNN）分类器的输出标签施加约束。我们提出了约束CNN（CCNN），一种使用新型损失函数来优化CNN的输出空间（即预测标签分布）上的任何线性约束集的方法。我们的损失公式很容易优化，可以直接纳入标准随机梯度下降优化。关键的想法是将训练目标称为线性模型的双凸优化，然后放松到非线性深度网络。大量的实验证明了我们新的学习框架的一般性。约束损失在弱监督的语义图像分割上产生最新的结果。我们进一步证明，增加更多的监督可以大大提高学习算法的性能。

##### URL
[https://arxiv.org/abs/1506.03648](https://arxiv.org/abs/1506.03648)

##### PDF
[https://arxiv.org/pdf/1506.03648](https://arxiv.org/pdf/1506.03648)

