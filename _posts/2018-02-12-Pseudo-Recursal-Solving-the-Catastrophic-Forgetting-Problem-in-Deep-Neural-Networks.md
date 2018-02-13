---
layout: post
title: "Pseudo-Recursal: Solving the Catastrophic Forgetting Problem in Deep Neural Networks"
date: 2018-02-12 03:51:41
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Craig Atkinson, Brendan McCane, Lech Szymanski, Anthony Robins
mathjax: true
---

* content
{:toc}

##### Abstract
In general, neural networks are not currently capable of learning tasks in a sequential fashion. When a novel, unrelated task is learnt by a neural network, it substantially forgets how to solve previously learnt tasks. One of the original solutions to this problem is pseudo-rehearsal, which involves learning the new task while rehearsing generated items representative of the previous task/s. This is very effective for simple tasks. However, pseudo-rehearsal has not yet been successfully applied to very complex tasks because in these tasks it is difficult to generate representative items. We accomplish pseudo-rehearsal by using a Generative Adversarial Network to generate items so that our deep network can learn to sequentially classify the CIFAR-10, SVHN and MNIST datasets. After training on all tasks, our network loses only 1.67% absolute accuracy on CIFAR-10 and gains 0.24% absolute accuracy on SVHN. Our model's performance is a substantial improvement compared to the current state of the art solution.

##### Abstract (translated by Google)
一般来说，神经网络目前不能以连续的方式学习任务。当一个新的，不相关的任务被神经网络所学习时，它就会忘记如何解决以前学过的任务。这个问题的原始解决方案之一是伪彩排，它涉及学习新任务，同时排练代表先前任务的生成项目。这对简单任务非常有效。然而，伪演习尚未成功应用于非常复杂的任务，因为在这些任务中难以生成具有代表性的项目。我们通过使用生成敌对​​网络生成项目来完成伪排练，以便我们的深层网络可以学习按顺序对CIFAR-10，SVHN和MNIST数据集进行分类。在完成所有任务的训练之后，我们的网络在CIFAR-10上的输出绝对精度仅为1.67％，SVHN的输出绝对精度为0.24％。与当前最先进的解决方案相比，我们的模型性能有了显着的提高。

##### URL
[http://arxiv.org/abs/1802.03875](http://arxiv.org/abs/1802.03875)

##### PDF
[http://arxiv.org/pdf/1802.03875](http://arxiv.org/pdf/1802.03875)

