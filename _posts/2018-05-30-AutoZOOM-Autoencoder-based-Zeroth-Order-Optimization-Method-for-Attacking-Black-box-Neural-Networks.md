---
layout: post
title: "AutoZOOM: Autoencoder-based Zeroth Order Optimization Method for Attacking Black-box Neural Networks"
date: 2018-05-30 01:39:34
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization
author: Chun-Chen Tu, Paishun Ting, Pin-Yu Chen, Sijia Liu, Huan Zhang, Jinfeng Yi, Cho-Jui Hsieh, Shin-Ming Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies have shown that adversarial examples in state-of-the-art image classifiers trained by deep neural networks (DNN) can be easily generated when the target model is transparent to an attacker, known as the white-box setting. However, when attacking a deployed machine learning service, one can only acquire the input-output correspondences of the target model; this is the so-called black-box attack setting. The major drawback of existing black-box attacks is the need for excessive model queries, which may lead to a false sense of model robustness due to inefficient query designs. To bridge this gap, we propose a generic framework for query-efficient black-box attacks. Our framework, AutoZOOM, which is short for Autoencoder-based Zeroth Order Optimization Method, has two novel building blocks towards efficient black-box attacks: (i) an adaptive random gradient estimation strategy to balance query counts and distortion, and (ii) an autoencoder trained offline with unlabeled data towards attack acceleration. Experimental results suggest that, by applying AutoZOOM to a state-of-the-art black-box attack (ZOO), a significant reduction in model queries can be achieved without sacrificing the attack success rate and the visual quality of the resulting adversarial examples. In particular, when compared to the standard ZOO method, AutoZOOM can consistently reduce the mean query counts in finding successful adversarial examples by at least 93% on MNIST, CIFAR-10 and ImageNet datasets. AutoZOOM's post-success fine-tuning can further reduce attack distortion.

##### Abstract (translated by Google)
最近的研究表明，当目标模型对攻击者透明时，可以容易地生成由深度神经网络（DNN）训练的最先进的图像分类器中的对抗示例，即白盒设置。但是，攻击部署的机器学习服务时，只能获取目标模型的输入输出对应关系，这就是所谓的黑盒攻击设置。现有黑盒攻击的主要缺点是需要过多的模型查询，这可能会导致由于低效的查询设计而导致的模型稳健性的错觉。为弥合这一差距，我们提出了一个查询效率黑盒攻击的通用框架。我们的框架AutoZOOM是基于自动编码器的零阶优化方法的缩写，它有两个新颖的构建模块，用于高效的黑盒攻击：（i）自适应随机梯度估计策略，以平衡查询计数和失真，以及（ii）自动编码器使用未标记的数据进行离线培训，以加速攻击。实验结果表明，通过将AutoZOOM应用于最先进的黑盒攻击（ZOO），可以在不牺牲攻击成功率和最终敌对示例的视觉质量的情况下实现模型查询的显着减少。特别是，与标准ZOO方法相比，AutoZOOM可以持续减少在MNIST，CIFAR-10和ImageNet数据集上找到成功对抗示例至少93％的平均查询次数。 AutoZOOM的成功后微调可以进一步减少攻击失真。

##### URL
[https://arxiv.org/abs/1805.11770](https://arxiv.org/abs/1805.11770)

##### PDF
[https://arxiv.org/pdf/1805.11770](https://arxiv.org/pdf/1805.11770)

