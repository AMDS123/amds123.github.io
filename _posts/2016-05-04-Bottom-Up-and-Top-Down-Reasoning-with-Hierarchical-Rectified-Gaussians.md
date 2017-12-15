---
layout: post
title: "Bottom-Up and Top-Down Reasoning with Hierarchical Rectified Gaussians"
date: 2016-05-04 22:50:35
categories: arXiv_CV
tags: arXiv_CV CNN Gradient_Descent
author: Peiyun Hu, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural nets (CNNs) have demonstrated remarkable performance in recent history. Such approaches tend to work in a unidirectional bottom-up feed-forward fashion. However, practical experience and biological evidence tells us that feedback plays a crucial role, particularly for detailed spatial understanding tasks. This work explores bidirectional architectures that also reason with top-down feedback: neural units are influenced by both lower and higher-level units. We do so by treating units as rectified latent variables in a quadratic energy function, which can be seen as a hierarchical Rectified Gaussian model (RGs). We show that RGs can be optimized with a quadratic program (QP), that can in turn be optimized with a recurrent neural network (with rectified linear units). This allows RGs to be trained with GPU-optimized gradient descent. From a theoretical perspective, RGs help establish a connection between CNNs and hierarchical probabilistic models. From a practical perspective, RGs are well suited for detailed spatial tasks that can benefit from top-down reasoning. We illustrate them on the challenging task of keypoint localization under occlusions, where local bottom-up evidence may be misleading. We demonstrate state-of-the-art results on challenging benchmarks.

##### Abstract (translated by Google)
卷积神经网络（CNNs）在近代史上表现出色。这种方法倾向于以单向自下而上的前馈方式工作。然而，实践经验和生物学证据告诉我们，反馈起着至关重要的作用，特别是对于详细的空间理解任务。这项工作探索双向架构，也是自上而下反馈的原因：神经单位受低级和高级单位的影响。我们这样做是通过将单位视为一个二次能量函数中的整数潜变量来实现的，这个二次能量函数可以看作是一个分层的整数高斯模型（RGs）。我们显示RG可以用二次程序（QP）进行优化，可以用递归神经网络（具有整流的线性单元）进行优化。这使得RG可以通过GPU优化的梯度下降进行训练。从理论的角度来看，RG有助于建立CNN和分层概率模型之间的联系。从实践的角度来看，RG非常适合于从自上而下的推理中获益的详细的空间任务。我们在关键点本地化的挑战性任务中说明了这些问题，这些地方自下而上的证据可能会引起误解。我们在具有挑战性的基准上展示最先进的成果。

##### URL
[https://arxiv.org/abs/1507.05699](https://arxiv.org/abs/1507.05699)

##### PDF
[https://arxiv.org/pdf/1507.05699](https://arxiv.org/pdf/1507.05699)

