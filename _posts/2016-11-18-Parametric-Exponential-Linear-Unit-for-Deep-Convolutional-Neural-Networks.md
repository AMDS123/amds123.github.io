---
layout: post
title: "Parametric Exponential Linear Unit for Deep Convolutional Neural Networks"
date: 2016-11-18 20:26:25
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning
author: Ludovic Trottier, Philippe Giguère, Brahim Chaib-draa
mathjax: true
---

* content
{:toc}

##### Abstract
The activation function is an important component in Convolutional Neural Networks (CNNs). For instance, recent breakthroughs in Deep Learning can be attributed to the Rectified Linear Unit (ReLU). Another recently proposed activation function, the Exponential Linear Unit (ELU), has the supplementary property of reducing bias shift without explicitly centering the values at zero. In this paper, we show that learning a parameterization of ELU improves its performance. We analyzed our proposed Parametric ELU (PELU) in the context of vanishing gradients and provide a gradient-based optimization framework. We conducted several experiments on CIFAR-10/100 and ImageNet with different network architectures, such as NiN, Overfeat, All-CNN and ResNet. Our results show that our PELU has relative error improvements over ELU of 4.45% and 5.68% on CIFAR-10 and 100, and as much as 7.28% with only 0.0003% parameter increase on ImageNet. We also observed that Vgg using PELU tended to prefer activations saturating closer to zero, as in ReLU, except at the last layer, which saturated near -2. Finally, other presented results suggest that varying the shape of the activations during training along with the other parameters helps controlling vanishing gradients and bias shift, thus facilitating learning.

##### Abstract (translated by Google)
激活函数是卷积神经网络（CNN）中的重要组成部分。例如，深度学习的最新突破可以归结为整流线性单位（ReLU）。另一个最近提出的激活函数，指数线性单位（ELU），具有减少偏移的补充性质，而不明确地将值置于零。在本文中，我们展示了学习ELU的参数化改进了它的性能。我们在消失梯度的情况下分析了我们提出的参数化ELU（PELU），并提供了基于梯度的优化框架。我们在CIFAR-10/100和ImageNet上进行了几个实验，采用不同的网络架构，如NiN，Overfeat，All-CNN和ResNet。我们的结果显示，在CIFAR-10和100上，我们的PELU的相对误差改善超过4.45％和5.68％，而在ImageNet上仅有0.0003％的参数增加，相对误差改善了7.28％。我们还观察到使用PELU的Vgg倾向于更喜欢饱和接近于零的激活，如在ReLU中一样，除了最后一层在-2附近饱和。最后，其他提出的结果表明，改变训练期间激活的形状以及其他参数有助于控制消失梯度和偏移，从而促进学习。

##### URL
[https://arxiv.org/abs/1605.09332](https://arxiv.org/abs/1605.09332)

##### PDF
[https://arxiv.org/pdf/1605.09332](https://arxiv.org/pdf/1605.09332)

