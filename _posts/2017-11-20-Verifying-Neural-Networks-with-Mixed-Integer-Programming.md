---
layout: post
title: "Verifying Neural Networks with Mixed Integer Programming"
date: 2017-11-20 15:05:33
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Vincent Tjeng, Russ Tedrake
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks have demonstrated considerable success in a wide variety of real-world problems. However, the presence of adversarial examples - slightly perturbed inputs that are misclassified with high confidence - limits our ability to guarantee performance for these networks in safety-critical applications. We demonstrate that, for networks that are piecewise affine (for example, deep networks with ReLU and maxpool units), proving no adversarial example exists - or finding the closest example if one does exist - can be naturally formulated as solving a mixed integer program. Solves for a fully-connected MNIST classifier with three hidden layers can be completed an order of magnitude faster than those of the best existing approach. To address the concern that adversarial examples are irrelevant because pixel-wise attacks are unlikely to happen in natural images, we search for adversaries over a natural class of perturbations written as convolutions with an adversarial blurring kernel. When searching over blurred images, we find that as opposed to pixelwise attacks, some misclassifications are impossible. Even more interestingly, a small fraction of input images are provably robust to blurs: every blurred version of the input is classified with the same, correct label.

##### Abstract (translated by Google)
神经网络已经在各种现实世界的问题中表现出相当大的成功。然而，存在对立的例子 - 微小的扰动输入，被高度置信地错误分类 - 限制了我们在安全关键应用中保证这些网络性能的能力。我们证明，对于分段仿射网络（例如，使用ReLU和maxpool单元的深度网络），证明没有敌对的例子存在 - 或者找到最接近的例子（如果存在的话） - 可以自然地被定义为求解混合整数程序。求解具有三个隐藏层的完全连接的MNIST分类器可以比现有最佳方法快完成一个数量级。为了解决这个问题，敌对的例子是无关紧要的，因为在自然图像中像素级的攻击不太可能发生，我们搜索对手的一个自然类的扰动，写成与敌对模糊内核卷积。当搜索模糊的图像，我们发现，而不是像素攻击，一些错误分类是不可能的。更有意思的是，输入图像的一小部分对模糊非常有效：输入的每个模糊版本都被分类为相同的正确标签。

##### URL
[https://arxiv.org/abs/1711.07356](https://arxiv.org/abs/1711.07356)

##### PDF
[https://arxiv.org/pdf/1711.07356](https://arxiv.org/pdf/1711.07356)

