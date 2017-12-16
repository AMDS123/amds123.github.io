---
layout: post
title: "Deep Neural Network Capacity"
date: 2017-10-03 18:59:27
categories: arXiv_CV
tags: arXiv_CV Regularization Inference Deep_Learning Quantitative
author: Aosen Wang, Hua Zhou, Wenyao Xu, Xin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep neural network exhibits its powerful superiority on information discrimination in many computer vision applications. However, the capacity of deep neural network architecture is still a mystery to the researchers. Intuitively, larger capacity of neural network can always deposit more information to improve the discrimination ability of the model. But, the learnable parameter scale is not feasible to estimate the capacity of deep neural network. Due to the overfitting, directly increasing hidden nodes number and hidden layer number are already demonstrated not necessary to effectively increase the network discrimination ability. In this paper, we propose a novel measurement, named "total valid bits", to evaluate the capacity of deep neural networks for exploring how to quantitatively understand the deep learning and the insights behind its super performance. Specifically, our scheme to retrieve the total valid bits incorporates the skilled techniques in both training phase and inference phase. In the network training, we design decimal weight regularization and 8-bit forward quantization to obtain the integer-oriented network representations. Moreover, we develop adaptive-bitwidth and non-uniform quantization strategy in the inference phase to find the neural network capacity, total valid bits. By allowing zero bitwidth, our adaptive-bitwidth quantization can execute the model reduction and valid bits finding simultaneously. In our extensive experiments, we first demonstrate that our total valid bits is a good indicator of neural network capacity. We also analyze the impact on network capacity from the network architecture and advanced training skills, such as dropout and batch normalization.

##### Abstract (translated by Google)
近年来，深度神经网络在许多计算机视觉应用中显示出其强大的信息歧视优势。然而，深度神经网络架构的能力仍然是研究人员的一个谜。直观地说，更大容量的神经网络总能存储更多的信息来提高模型的辨别能力。但是，学习参数尺度对于深度神经网络的容量估计是不可行的。由于过拟合，直接增加隐含节点数量和隐层数量已经不再有效提高网络辨识能力。在本文中，我们提出了一个新的测量方法，称为“总有效位”，来评估深度神经网络的能力，以探索如何定量地理解深度学习和超强表现背后的真知灼见。具体来说，我们的检索总有效位的方案在训练阶段和推理阶段都包含熟练的技术。在网络训练中，我们设计了十进制加权正则化和8比特正向量化来获得面向整数的网络表示。此外，我们在推理阶段开发自适应位宽和非均匀量化策略来查找神经网络容量，总有效位数。通过允许零位宽，我们的自适应位宽量化可以同时执行模型缩减和有效位查找。在我们广泛的实验中，我们首先证明了我们的总有效位是神经网络容量的一个很好的指标。我们还分析了网络架构对网络容量的影响以及高级培训技能，如退出和批量规范化。

##### URL
[https://arxiv.org/abs/1708.05029](https://arxiv.org/abs/1708.05029)

##### PDF
[https://arxiv.org/e-print/1708.05029](https://arxiv.org/e-print/1708.05029)

