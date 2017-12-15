---
layout: post
title: "Learning to Poke by Poking: Experiential Learning of Intuitive Physics"
date: 2017-02-15 22:53:52
categories: arXiv_CV
tags: arXiv_CV
author: Pulkit Agrawal, Ashvin Nair, Pieter Abbeel, Jitendra Malik, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate an experiential learning paradigm for acquiring an internal model of intuitive physics. Our model is evaluated on a real-world robotic manipulation task that requires displacing objects to target locations by poking. The robot gathered over 400 hours of experience by executing more than 100K pokes on different objects. We propose a novel approach based on deep neural networks for modeling the dynamics of robot's interactions directly from images, by jointly estimating forward and inverse models of dynamics. The inverse model objective provides supervision to construct informative visual features, which the forward model can then predict and in turn regularize the feature space for the inverse model. The interplay between these two objectives creates useful, accurate models that can then be used for multi-step decision making. This formulation has the additional benefit that it is possible to learn forward models in an abstract feature space and thus alleviate the need of predicting pixels. Our experiments show that this joint modeling approach outperforms alternative methods.

##### Abstract (translated by Google)
我们调查一个经验学习范式，以获取直观物理学的内部模型。我们的模型是在一个真实的机器人操作任务上进行评估的，需要通过拨动来将物体移动到目标位置。机器人通过在不同的物体上执行超过100K的点击，聚集了超过400小时的经验。我们提出了一种新的基于深度神经网络的方法，通过联合估计动态的正向和反向模型来直接从图像中模拟机器人相互作用的动态。逆模型目标提供监督，以建立信息的视觉特征，正向模型可以预测，然后调整逆模型的特征空间。这两个目标之间的相互作用产生了有用的，准确的模型，然后可以用于多步决策。这个公式还有另外一个好处，就是可以在抽象的特征空间中学习正演模型，从而减少预测像素的需要。我们的实验表明，这种联合建模方法优于其他方法。

##### URL
[https://arxiv.org/abs/1606.07419](https://arxiv.org/abs/1606.07419)

##### PDF
[https://arxiv.org/pdf/1606.07419](https://arxiv.org/pdf/1606.07419)

