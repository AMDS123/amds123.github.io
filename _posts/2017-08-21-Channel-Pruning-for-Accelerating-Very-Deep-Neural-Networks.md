---
layout: post
title: "Channel Pruning for Accelerating Very Deep Neural Networks"
date: 2017-08-21 09:44:26
categories: arXiv_CV
tags: arXiv_CV CNN
author: Yihui He, Xiangyu Zhang, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a new channel pruning method to accelerate very deep convolutional neural networks.Given a trained CNN model, we propose an iterative two-step algorithm to effectively prune each layer, by a LASSO regression based channel selection and least square reconstruction. We further generalize this algorithm to multi-layer and multi-branch cases. Our method reduces the accumulated error and enhance the compatibility with various architectures. Our pruned VGG-16 achieves the state-of-the-art results by 5x speed-up along with only 0.3% increase of error. More importantly, our method is able to accelerate modern networks like ResNet, Xception and suffers only 1.4%, 1.0% accuracy loss under 2x speed-up respectively, which is significant. Code has been made publicly available.

##### Abstract (translated by Google)
在本文中，我们引入了一种新的信道修剪方法来加速非常深的卷积神经网络。给出一个训练好的CNN模型，我们提出了一种迭代两步算法来有效地修剪每一层，通过基于LASSO回归的信道选择和最小二乘重构。我们进一步推广这个算法到多层和多分支的情况。我们的方法减少了累积误差，提高了与各种架构的兼容性。我们修剪的VGG-16通过5倍的加速实现了最先进的结果，误差仅增加了0.3％。更重要的是，我们的方法能够加快ResNet，Xception等现代网络的速度，分别只有1.4％，1.0倍的精度损失，这是显着的。代码已经公开。

##### URL
[https://arxiv.org/abs/1707.06168](https://arxiv.org/abs/1707.06168)

##### PDF
[https://arxiv.org/pdf/1707.06168](https://arxiv.org/pdf/1707.06168)

