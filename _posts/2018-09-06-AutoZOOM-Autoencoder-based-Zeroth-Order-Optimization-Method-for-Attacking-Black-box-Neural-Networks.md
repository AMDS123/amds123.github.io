---
layout: post
title: "AutoZOOM: Autoencoder-based Zeroth Order Optimization Method for Attacking Black-box Neural Networks"
date: 2018-09-06 21:03:43
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization
author: Chun-Chen Tu, Paishun Ting, Pin-Yu Chen, Sijia Liu, Huan Zhang, Jinfeng Yi, Cho-Jui Hsieh, Shin-Ming Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies have shown that adversarial examples in state-of-the-art image classifiers trained by deep neural networks (DNN) can be easily generated when the target model is transparent to an attacker, known as the white-box setting. However, when attacking a deployed machine learning service, one can only acquire the input-output correspondences of the target model; this is the so-called black-box attack setting. The major drawback of existing black-box attacks is the need for excessive model queries, which may give a false sense of model robustness due to inefficient query designs. To bridge this gap, we propose a generic framework for query-efficient black-box attacks. Our framework, AutoZOOM, which is short for Autoencoder-based Zeroth Order Optimization Method, has two novel building blocks towards efficient black-box attacks: (i) an adaptive random gradient estimation strategy to balance query counts and distortion, and (ii) an autoencoder that is either trained offline with unlabeled data or a bilinear resizing operation for attack acceleration. Experimental results suggest that, by applying AutoZOOM to a state-of-the-art black-box attack (ZOO), a significant reduction in model queries can be achieved without sacrificing the attack success rate and the visual quality of the resulting adversarial examples. In particular, when compared to the standard ZOO method, AutoZOOM can consistently reduce the mean query counts in finding successful adversarial examples (or reaching the same distortion level) by at least 93% on MNIST, CIFAR-10 and ImageNet datasets, leading to novel insights on adversarial robustness.

##### Abstract (translated by Google)
最近的研究表明，当目标模型对攻击者透明时，可以很容易地生成由深度神经网络（DNN）训练的最先进图像分类器中的对抗性示例，称为白盒设置。但是，在攻击部署的机器学习服务时，只能获取目标模型的输入输出对应关系;这就是所谓的黑盒攻击设置。现有黑盒攻击的主要缺点是需要过多的模型查询，这可能由于低效的查询设计而给出错误的模型鲁棒性。为了弥补这一差距，我们提出了一种用于查询高效黑盒攻击的通用框架。我们的框架AutoZOOM是基于Autoencoder的Zeroth订单优化方法的缩写，它有两个新的构建模块用于有效的黑盒攻击：（i）自适应随机梯度估计策略，用于平衡查询计数和失真，以及（ii）自动编码器，可以使用未标记的数据进行离线训练，也可以使用双线性调整大小来进行攻击加速。实验结果表明，通过将AutoZOOM应用于最先进的黑盒攻击（ZOO），可以在不牺牲攻击成功率和所得对抗性示例的视觉质量的情况下实现模型查询的显着减少。特别是，与标准ZOO方法相比，AutoZOOM可以在MNIST，CIFAR-10和ImageNet数据集中找到成功的对抗示例（或达到相同的失真级别）至少93％，从而始终如一地减少平均查询计数对抗敌对稳健性的见解。

##### URL
[http://arxiv.org/abs/1805.11770](http://arxiv.org/abs/1805.11770)

##### PDF
[http://arxiv.org/pdf/1805.11770](http://arxiv.org/pdf/1805.11770)

