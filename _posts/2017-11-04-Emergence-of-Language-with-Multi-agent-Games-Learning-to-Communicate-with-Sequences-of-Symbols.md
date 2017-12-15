---
layout: post
title: "Emergence of Language with Multi-agent Games: Learning to Communicate with Sequences of Symbols"
date: 2017-11-04 15:04:51
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Serhii Havrylov, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to communicate through interaction, rather than relying on explicit supervision, is often considered a prerequisite for developing a general AI. We study a setting where two agents engage in playing a referential game and, from scratch, develop a communication protocol necessary to succeed in this game. Unlike previous work, we require that messages they exchange, both at train and test time, are in the form of a language (i.e. sequences of discrete symbols). We compare a reinforcement learning approach and one using a differentiable relaxation (straight-through Gumbel-softmax estimator) and observe that the latter is much faster to converge and it results in more effective protocols. Interestingly, we also observe that the protocol we induce by optimizing the communication success exhibits a degree of compositionality and variability (i.e. the same information can be phrased in different ways), both properties characteristic of natural languages. As the ultimate goal is to ensure that communication is accomplished in natural language, we also perform experiments where we inject prior information about natural language into our model and study properties of the resulting protocol.

##### Abstract (translated by Google)
学习通过互动交流，而不是依靠明确的监督，往往被认为是发展一般性人工智能的先决条件。我们研究了两个代理商参与游戏参考的设置，从头开始制定一个通信协议，以便在这个游戏中取得成功。与以前的工作不同，我们要求它们在训练和测试时间交换的消息都是以语言（即离散符号序列）的形式出现的。我们将强化学习方法与使用可微松弛（直通Gumbel-softmax估计器）的方法进行比较，并观察后者的收敛速度要快得多，并导致更有效的协议。有趣的是，我们也观察到，我们通过优化沟通成功而诱导的协议表现出一定程度的组合性和变异性（即相同的信息可以用不同的方式表达），这两种性质都是自然语言的特征。最终的目标是确保沟通以自然语言完成，我们也进行实验，将自然语言的先验信息注入到我们的模型中，并研究生成的协议的属性。

##### URL
[https://arxiv.org/abs/1705.11192](https://arxiv.org/abs/1705.11192)

##### PDF
[https://arxiv.org/pdf/1705.11192](https://arxiv.org/pdf/1705.11192)

