---
layout: post
title: "Training Deep Networks with Structured Layers by Matrix Backpropagation"
date: 2016-04-14 11:30:39
categories: arXiv_CV
tags: arXiv_CV Segmentation Recognition
author: Catalin Ionescu, Orestis Vantzos, Cristian Sminchisescu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network architectures have recently produced excellent results in a variety of areas in artificial intelligence and visual recognition, well surpassing traditional shallow architectures trained using hand-designed features. The power of deep networks stems both from their ability to perform local computations followed by pointwise non-linearities over increasingly larger receptive fields, and from the simplicity and scalability of the gradient-descent training procedure based on backpropagation. An open problem is the inclusion of layers that perform global, structured matrix computations like segmentation (e.g. normalized cuts) or higher-order pooling (e.g. log-tangent space metrics defined over the manifold of symmetric positive definite matrices) while preserving the validity and efficiency of an end-to-end deep training framework. In this paper we propose a sound mathematical apparatus to formally integrate global structured computation into deep computation architectures. At the heart of our methodology is the development of the theory and practice of backpropagation that generalizes to the calculus of adjoint matrix variations. The proposed matrix backpropagation methodology applies broadly to a variety of problems in machine learning or computational perception. Here we illustrate it by performing visual segmentation experiments using the BSDS and MSCOCO benchmarks, where we show that deep networks relying on second-order pooling and normalized cuts layers, trained end-to-end using matrix backpropagation, outperform counterparts that do not take advantage of such global layers.

##### Abstract (translated by Google)
深度神经网络架构最近在人工智能和视觉识别的各个领域都取得了出色的成果，远远超过了使用手工设计特征训练的传统浅层架构。深层网络的力量源自于它们执行本地计算的能力，随后在越来越大的接受域上逐步呈现非线性，以及基于反向传播的梯度下降训练过程的简单性和可扩展性。一个公开的问题是包含了执行像分割（例如归一化切割）或更高阶共享（例如，在对称正定矩阵的流形上定义的对数正切空间度量）的全局结构化矩阵计算的层，同时保持有效性和效率是一个端到端的深度训练框架。在本文中，我们提出了一个合理的数学设备，将全局结构化计算正式集成到深度计算架构中。我们方法论的核心是反向传播的理论和实践的发展，推广到伴随矩阵变化的演算。所提出的矩阵反向传播方法广泛地应用于机器学习或计算感知中的各种问题。在这里，我们通过使用BSDS和MSCOCO基准进行视觉分割实验来说明这一点，其中我们展示了依赖于二阶聚合和归一化切割层的深度网络，使用矩阵反向传播进行端对端训练，胜过没有利用的对手这样的全球层次。

##### URL
[https://arxiv.org/abs/1509.07838](https://arxiv.org/abs/1509.07838)

##### PDF
[https://arxiv.org/pdf/1509.07838](https://arxiv.org/pdf/1509.07838)

