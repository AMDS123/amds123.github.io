---
layout: post
title: "One Network to Solve Them All --- Solving Linear Inverse Problems using Deep Projection Models"
date: 2017-03-29 07:20:10
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Optimization Deep_Learning
author: J. H. Rick Chang, Chun-Liang Li, Barnabas Poczos, B. V. K. Vijaya Kumar, Aswin C. Sankaranarayanan
mathjax: true
---

* content
{:toc}

##### Abstract
While deep learning methods have achieved state-of-the-art performance in many challenging inverse problems like image inpainting and super-resolution, they invariably involve problem-specific training of the networks. Under this approach, different problems require different networks. In scenarios where we need to solve a wide variety of problems, e.g., on a mobile camera, it is inefficient and costly to use these specially-trained networks. On the other hand, traditional methods using signal priors can be used in all linear inverse problems but often have worse performance on challenging tasks. In this work, we provide a middle ground between the two kinds of methods --- we propose a general framework to train a single deep neural network that solves arbitrary linear inverse problems. The proposed network acts as a proximal operator for an optimization algorithm and projects non-image signals onto the set of natural images defined by the decision boundary of a classifier. In our experiments, the proposed framework demonstrates superior performance over traditional methods using a wavelet sparsity prior and achieves comparable performance of specially-trained networks on tasks including compressive sensing and pixel-wise inpainting.

##### Abstract (translated by Google)
虽然深度学习方法已经在诸如图像修复和超分辨率等许多具有挑战性的逆向问题中取得了最先进的性能，但它们总是涉及网络的特定于问题的训练。在这种方式下，不同的问题需要不同的网络。在需要解决各种问题的情况下，例如在移动照相机上，使用这些经过特殊训练的网络是低效和昂贵的。另一方面，使用信号先验的传统方法可以用于所有的线性反问题，但是在具有挑战性的任务上通常具有更差的性能。在这项工作中，我们提供了两种方法的中间地带 - 我们提出了一个通用的框架来训练一个单一的深度神经网络，解决了任意的线性反问题。所提出的网络作为优化算法的近端算子，并将非图像信号投影到由分类器的决策边界所定义的自然图像集上。在我们的实验中，所提出的框架比使用小波稀疏先验的传统方法表现出优越的性能，并且在包括压缩感测和像素明显的修复的任务中实现了经特殊训练的网络的可比较的性能。

##### URL
[https://arxiv.org/abs/1703.09912](https://arxiv.org/abs/1703.09912)

##### PDF
[https://arxiv.org/pdf/1703.09912](https://arxiv.org/pdf/1703.09912)

