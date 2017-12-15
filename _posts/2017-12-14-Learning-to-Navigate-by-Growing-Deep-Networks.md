---
layout: post
title: "Learning to Navigate by Growing Deep Networks"
date: 2017-12-14 03:58:23
categories: arXiv_CV
tags: arXiv_CV Knowledge Reinforcement_Learning Deep_Learning
author: Thushan Ganegedara, Lionel Ott, Fabio Ramos
mathjax: true
---

* content
{:toc}

##### Abstract
Adaptability is central to autonomy. Intuitively, for high-dimensional learning problems such as navigating based on vision, internal models with higher complexity allow to accurately encode the information available. However, most learning methods rely on models with a fixed structure and complexity. In this paper, we present a self-supervised framework for robots to learn to navigate, without any prior knowledge of the environment, by incrementally building the structure of a deep network as new data becomes available. Our framework captures images from a monocular camera and self labels the images to continuously train and predict actions from a computationally efficient adaptive deep architecture based on Autoencoders (AE), in a self-supervised fashion. The deep architecture, named Reinforced Adaptive Denoising Autoencoders (RA-DAE), uses reinforcement learning to dynamically change the network structure by adding or removing neurons. Experiments were conducted in simulation and real-world indoor and outdoor environments to assess the potential of self-supervised navigation. RA-DAE demonstrates better performance than equivalent non-adaptive deep learning alternatives and can continue to expand its knowledge, trading-off past and present information.

##### Abstract (translated by Google)
适应性是自治的核心。直观地，对于诸如基于视觉的导航的高维学习问题，具有较高复杂度的内部模型允许对可用信息进行精确编码。然而，大多数学习方法依赖于结构和复杂性固定的模型。在本文中，我们提出了一个自我监督的机器人框架，在没有任何环境知识的情况下学习导航，随着新数据的可用，逐步构建深度网络的结构。我们的框架捕捉单眼相机拍摄的图像，并以自我监督的方式自我标记图像，从基于自动编码器（AE）的计算高效自适应深层架构中不断训练和预测动作。被称为增强自适应去噪自动编码器（RA-DAE）的深层架构使用强化学习来通过添加或去除神经元来动态改变网络结构。在模拟和真实世界的室内和室外环境中进行实验以评估自监督导航的潜力。 RA-DAE比等效的非适应性深度学习方法表现出更好的性能，并且可以继续扩展知识，取舍过去和现在的信息。

##### URL
[http://arxiv.org/abs/1712.05084](http://arxiv.org/abs/1712.05084)

##### PDF
[http://arxiv.org/pdf/1712.05084](http://arxiv.org/pdf/1712.05084)

