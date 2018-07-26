---
layout: post
title: "Conditional Information Gain Networks"
date: 2018-07-25 11:26:46
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Ufuk Can Bi&#xe7;ici, Cem Keskin, Lale Akarun
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network models owe their representational power to the high number of learnable parameters. It is often infeasible to run these largely parametrized deep models in limited resource environments, like mobile phones. Network models employing conditional computing are able to reduce computational requirements while achieving high representational power, with their ability to model hierarchies. We propose Conditional Information Gain Networks, which allow the feed forward deep neural networks to execute conditionally, skipping parts of the model based on the sample and the decision mechanisms inserted in the architecture. These decision mechanisms are trained using cost functions based on differentiable Information Gain, inspired by the training procedures of decision trees. These information gain based decision mechanisms are differentiable and can be trained end-to-end using a unified framework with a general cost function, covering both classification and decision losses. We test the effectiveness of the proposed method on MNIST and recently introduced Fashion MNIST datasets and show that our information gain based conditional execution approach can achieve better or comparable classification results using significantly fewer parameters, compared to standard convolutional neural network baselines.

##### Abstract (translated by Google)
深度神经网络模型的代表能力归功于大量可学习的参数。在有限的资源环境（如移动电话）中运行这些基本上参数化的深度模型通常是不可行的。采用条件计算的网络模型能够在实现高代表性能力的同时降低计算要求，并具有模拟层次结构的能力。我们提出条件信息增益网络，它允许前馈深度神经网络有条件地执行，基于样本和插入到架构中的决策机制跳过模型的部分。这些决策机制使用基于可区分信息增益的成本函数进行训练，其灵感来自决策树的训练过程。这些基于信息增益的决策机制是可区分的，可以使用具有一般成本函数的统一框架进行端到端的培训，涵盖分类和决策损失。我们测试了所提出的方法对MNIST的有效性，并且最近引入了Fashion MNIST数据集，并且表明，与标准卷积神经网络基线相比，基于信息增益的条件执行方法可以使用显着更少的参数实现更好或可比较的分类结果。

##### URL
[http://arxiv.org/abs/1807.09534](http://arxiv.org/abs/1807.09534)

##### PDF
[http://arxiv.org/pdf/1807.09534](http://arxiv.org/pdf/1807.09534)

