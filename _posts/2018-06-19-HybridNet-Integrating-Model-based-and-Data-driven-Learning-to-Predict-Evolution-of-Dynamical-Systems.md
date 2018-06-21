---
layout: post
title: "HybridNet: Integrating Model-based and Data-driven Learning to Predict Evolution of Dynamical Systems"
date: 2018-06-19 19:32:42
categories: arXiv_AI
tags: arXiv_AI Knowledge CNN RNN Deep_Learning Prediction
author: Yun Long, Xueyuan She, Saibal Mukhopadhyay
mathjax: true
---

* content
{:toc}

##### Abstract
The robotic systems continuously interact with complex dynamical systems in the physical world. Reliable predictions of spatiotemporal evolution of these dynamical systems, with limited knowledge of system dynamics, are crucial for autonomous operation. In this paper, we present HybridNet, a framework that integrates data-driven deep learning and model-driven computation to reliably predict spatiotemporal evolution of a dynamical systems even with in-exact knowledge of their parameters. A data-driven deep neural network (DNN) with Convolutional LSTM (ConvLSTM) as the backbone is employed to predict the time-varying evolution of the external forces/perturbations. On the other hand, the model-driven computation is performed using Cellular Neural Network (CeNN), a neuro-inspired algorithm to model dynamical systems defined by coupled partial differential equations (PDEs). CeNN converts the intricate numerical computation into a series of convolution operations, enabling a trainable PDE solver. With a feedback control loop, HybridNet can learn the physical parameters governing the system's dynamics in real-time, and accordingly adapt the computation models to enhance prediction accuracy for time-evolving dynamical systems. The experimental results on two dynamical systems, namely, heat convection-diffusion system, and fluid dynamical system, demonstrate that the HybridNet produces higher accuracy than the state-of-the-art deep learning based approach.

##### Abstract (translated by Google)
机器人系统不断与物理世界中的复杂动力系统相互作用。对这些动态系统的时空演化的可靠预测，对系统动力学知识有限，对于自主操作至关重要。在本文中，我们介绍HybridNet，这是一个将数据驱动的深度学习和模型驱动计算相结合的框架，可以可靠地预测动态系统的时空演化，即使对参数有精确的了解。采用以Convolutional LSTM（ConvLSTM）为骨干的数据驱动的深度神经网络（DNN）来预测外部力/扰动的时变演变。另一方面，使用细胞神经网络（Cellular Neural Network，CeNN）进行模型驱动的计算，这是一种神经启发式算法，用于模拟由偏微分方程（PDE）定义的动力学系统。 CeNN将复杂的数值计算转换为一系列卷积运算，从而实现可训练的PDE求解器。通过反馈控制回路，HybridNet可以实时掌握控制系统动态的物理参数，并相应调整计算模型以提高时间演化动力系统的预测精度。在两个动力学系统，即热对流扩散系统和流体动力系统上的实验结果表明，HybridNet比现有技术的深度学习方法产生更高的准确性。

##### URL
[http://arxiv.org/abs/1806.07439](http://arxiv.org/abs/1806.07439)

##### PDF
[http://arxiv.org/pdf/1806.07439](http://arxiv.org/pdf/1806.07439)

