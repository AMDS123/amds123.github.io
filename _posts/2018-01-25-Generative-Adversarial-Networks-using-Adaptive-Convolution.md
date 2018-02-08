---
layout: post
title: "Generative Adversarial Networks using Adaptive Convolution"
date: 2018-01-25 23:49:19
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Nhat M. Nguyen, Nilanjan Ray
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing GANs architectures that generate images use transposed convolution or resize-convolution as their upsampling algorithm from lower to higher resolution feature maps in the generator. We argue that this kind of fixed operation is problematic for GANs to model objects that have very different visual appearances. We propose a novel adaptive convolution method that learns the upsampling algorithm based on the local context at each location to address this problem. We modify a baseline GANs architecture by replacing normal convolutions with adaptive convolutions in the generator. Experiments on CIFAR-10 dataset show that our modified models improve the baseline model by a large margin. Furthermore, our models achieve state-of-the-art performance on CIFAR-10 and STL-10 datasets in the unsupervised setting.

##### Abstract (translated by Google)
大多数现有的生成图像的GAN体系结构使用卷积或调整大小卷积作为它们的上采样算法，从发生器中的较低分辨率特征映射到较高分辨率特征映射。我们认为这种固定操作对于GAN来模拟具有非常不同视觉外观的物体是有问题的。我们提出了一种新的自适应卷积方法，学习基于每个位置的本地上下文的上采样算法来解决这个问题。我们通过用发生器中的自适应卷积替换正常卷积来修改基线GAN结构。在CIFAR-10数据集上的实验表明，我们的改进模型大大改善了基线模型。此外，我们的模型在无监督设置下在CIFAR-10和STL-10数据集上实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1802.02226](https://arxiv.org/abs/1802.02226)

##### PDF
[https://arxiv.org/pdf/1802.02226](https://arxiv.org/pdf/1802.02226)

