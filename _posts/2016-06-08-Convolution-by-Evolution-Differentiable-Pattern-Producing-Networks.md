---
layout: post
title: "Convolution by Evolution: Differentiable Pattern Producing Networks"
date: 2016-06-08 14:37:39
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Chrisantha Fernando, Dylan Banarse, Malcolm Reynolds, Frederic Besse, David Pfau, Max Jaderberg, Marc Lanctot, Daan Wierstra
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we introduce a differentiable version of the Compositional Pattern Producing Network, called the DPPN. Unlike a standard CPPN, the topology of a DPPN is evolved but the weights are learned. A Lamarckian algorithm, that combines evolution and learning, produces DPPNs to reconstruct an image. Our main result is that DPPNs can be evolved/trained to compress the weights of a denoising autoencoder from 157684 to roughly 200 parameters, while achieving a reconstruction accuracy comparable to a fully connected network with more than two orders of magnitude more parameters. The regularization ability of the DPPN allows it to rediscover (approximate) convolutional network architectures embedded within a fully connected architecture. Such convolutional architectures are the current state of the art for many computer vision applications, so it is satisfying that DPPNs are capable of discovering this structure rather than having to build it in by design. DPPNs exhibit better generalization when tested on the Omniglot dataset after being trained on MNIST, than directly encoded fully connected autoencoders. DPPNs are therefore a new framework for integrating learning and evolution.

##### Abstract (translated by Google)
在这项工作中，我们介绍一个称为DPPN的组合模式生成网络的可微版本。与标准的CPPN不同，DPPN的拓扑结构是演变的，但权重是学习的。结合进化和学习的拉马克算法产生DPPN来重构图像。我们的主要结果是可以演进/训练DPPN以将去噪自动编码器的权重从157684压缩到大约200个参数，同时实现与完全连接的网络相比具有超过两个数量级的更多参数的重构精度。 DPPN的正则化能力使其能够重新发现嵌入在完全连接的体系结构中的（近似的）卷积网络体系结构。这种卷积架构是当前许多计算机视觉应用的技术发展水平，所以DPPN能够发现这种结构而不是通过设计来构建它是令人满意的。当在MNIST上训练之后，在Omniglot数据集上进行测试时，DPPN比直接编码的完全连接的自动编码器显示出更好的概括性。 DPPN因此是一个整合学习和演化的新框架。

##### URL
[https://arxiv.org/abs/1606.02580](https://arxiv.org/abs/1606.02580)

##### PDF
[https://arxiv.org/pdf/1606.02580](https://arxiv.org/pdf/1606.02580)

