---
layout: post
title: "Memory Aware Synapses: Learning what to forget"
date: 2017-11-27 09:48:44
categories: arXiv_CV
tags: arXiv_CV Knowledge Embedding Recognition
author: Rahaf Aljundi, Francesca Babiloni, Mohamed Elhoseiny, Marcus Rohrbach, Tinne Tuytelaars
mathjax: true
---

* content
{:toc}

##### Abstract
Humans can learn in a continuous manner. Old rarely utilized knowledge can be overwritten by new incoming information while important, frequently used knowledge is prevented from being erased. In artificial learning systems, lifelong learning so far has focused mainly on accumulating knowledge over tasks and overcoming catastrophic forgetting. In this paper, we argue that, given the limited model capacity and the unlimited new information to be learned, knowledge has to be preserved or erased selectively. Inspired by neuroplasticity, we propose an online method to compute the importance of the parameters of a neural network, based on the data that the network is actively applied to, in an unsupervised manner. After learning a task, whenever a sample is fed to the network, we accumulate an importance measure for each parameter of the network, based on how sensitive the predicted output is to a change in this parameter. When learning a new task, changes to important parameters are penalized. We show that a local version of our method is a direct application of Hebb's rule in identifying the important connections between neurons. We test our method on a sequence of object recognition tasks and on the challenging problem of learning an embedding in a continuous manner. We show state of the art performance and the ability to adapt the importance of the parameters towards what the network needs (not) to forget, which may be different for different test conditions.

##### Abstract (translated by Google)
人类可以连续学习。旧的很少利用的知识可以被新的输入信息覆盖，而重要的，经常使用的知识被防止被删除。在人工学习系统中，到目前为止，终身学习主要集中在积累任务知识和克服灾难性遗忘方面。在本文中，我们认为，鉴于有限的模型能力和无限的新知识，需要有选择地保存或删除知识。受神经可塑性的启发，我们提出一种在线方法，以无监督的方式基于网络主动应用的数据来计算神经网络参数的重要性。学习任务后，无论何时将样本馈送到网络，我们都会根据预测输出对此参数的变化的敏感程度，为网络的每个参数积累一个重要度量。学习新任务时，对重要参数的更改将受到惩罚。我们表明，我们的方法的本地版本是直接应用Hebb的规则，以确定神经元之间的重要联系。我们测试我们的方法在一系列的对象识别任务和连续学习嵌入的挑战性问题。我们展示了最先进的性能和适应网络需要（不）忘记的参数的重要性的能力，这对于不同的测试条件可能是不同的。

##### URL
[https://arxiv.org/abs/1711.09601](https://arxiv.org/abs/1711.09601)

##### PDF
[https://arxiv.org/pdf/1711.09601](https://arxiv.org/pdf/1711.09601)

