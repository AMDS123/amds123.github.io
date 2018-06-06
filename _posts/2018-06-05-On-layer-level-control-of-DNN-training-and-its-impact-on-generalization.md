---
layout: post
title: "On layer-level control of DNN training and its impact on generalization"
date: 2018-06-05 10:39:21
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning
author: Simon Carbonnelle, Christophe De Vleeschouwer
mathjax: true
---

* content
{:toc}

##### Abstract
The generalization ability of a neural network depends on the optimization procedure used for training it. For practitioners and theoreticians, it is essential to identify which properties of the optimization procedure influence generalization. In this paper, we observe that prioritizing the training of distinct layers in a network significantly impacts its generalization ability, sometimes causing differences of up to 30% in test accuracy. In order to better monitor and control such prioritization, we propose to define layer-level training speed as the rotation rate of the layer's weight vector (denoted by layer rotation rate hereafter), and develop Layca, an optimization algorithm that enables direct control over it through each layer's learning rate parameter, without being affected by gradient propagation phenomena (e.g. vanishing gradients). We show that controlling layer rotation rates enables Layca to significantly outperform SGD with the same amount of learning rate tuning on three different tasks (up to 10% test error improvement). Furthermore, we provide experiments that suggest that several intriguing observations related to the training of deep models, i.e. the presence of plateaus in learning curves, the impact of weight decay, and the bad generalization properties of adaptive gradient methods, are all due to specific configurations of layer rotation rates. Overall, our work reveals that layer rotation rates are an important factor for generalization, and that monitoring it should be a key component of any deep learning experiment.

##### Abstract (translated by Google)
神经网络的泛化能力取决于用于训练它的优化程序。对于从业者和理论家而言，确定优化程序的哪些属性影响泛化至关重要。在本文中，我们观察到优先考虑网络中不同层次的训练显着影响其泛化能力，有时会导致测试精度高达30％的差异。为了更好地监控和控制这种优先级，我们提出将层级训练速度定义为层的权重向量的旋转速率（以下称为层旋转速率），并开发Layca，这是一种能够直接控制它的优化算法通过每层的学习速率参数，而不受梯度传播现象（例如消失梯度）的影响。我们发现，控制层转速可以使Layca在三个不同任务（高达10％的测试错误改进）上以相同的学习速率调整量显着优于SGD。此外，我们提供的实验表明，与深层模型的训练有关的几个有趣的观察结果，即学习曲线中的高原，重量衰减的影响以及自适应梯度方法的不良泛化性质都是由于特定的配置的层转速。总的来说，我们的工作表明层旋转速率是泛化的重要因素，并且监视它应该是任何深度学习实验的关键组成部分。

##### URL
[http://arxiv.org/abs/1806.01603](http://arxiv.org/abs/1806.01603)

##### PDF
[http://arxiv.org/pdf/1806.01603](http://arxiv.org/pdf/1806.01603)

