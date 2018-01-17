---
layout: post
title: "Learning what to share between loosely related tasks"
date: 2018-01-16 14:05:37
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Sebastian Ruder, Joachim Bingel, Isabelle Augenstein, Anders S&#xf8;gaard
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task learning is motivated by the observation that humans bring to bear what they know about related problems when solving new ones. Similarly, deep neural networks can profit from related tasks by sharing parameters with other networks. However, humans do not consciously decide to transfer knowledge between tasks. In Natural Language Processing (NLP), it is hard to predict if sharing will lead to improvements, particularly if tasks are only loosely related. To overcome this, we introduce Sluice Networks, a general framework for multi-task learning where trainable parameters control the amount of sharing. Our framework generalizes previous proposals in enabling sharing of all combinations of subspaces, layers, and skip connections. We perform experiments on three task pairs, and across seven different domains, using data from OntoNotes 5.0, and achieve up to 15% average error reductions over common approaches to multi-task learning. We show that a) label entropy is predictive of gains in sluice networks, confirming findings for hard parameter sharing and b) while sluice networks easily fit noise, they are robust across domains in practice.

##### Abstract (translated by Google)
多任务学习的动机是观察到人类在解决新问题时带来了解有关问题的知识。类似地，深度神经网络可以通过与其他网络共享参数从相关任务中获益。但是，人类不会有意识地决定在任务之间转移知识。在自然语言处理（NLP）中，很难预测共享是否会导致改进，特别是在任务只是松散相关的情况下。为了克服这个问题，我们引入Sluice Networks，一个多任务学习的通用框架，其中可训练的参数控制共享的数量。我们的框架概括了先前的提议，使得能够共享子空间，层和跳过连接的所有组合。我们使用来自OntoNotes 5.0的数据在三个任务对和七个不同的域之间进行实验，并且与通常的多任务学习方法相比，实现了高达15％的平均错误减少率。我们表明：a）标签熵是预测水闸网络中的增益，确认硬参数共享的结果; b）当水闸网络容易适应噪声时，它们在实践中跨域强健。

##### URL
[http://arxiv.org/abs/1705.08142](http://arxiv.org/abs/1705.08142)

##### PDF
[http://arxiv.org/pdf/1705.08142](http://arxiv.org/pdf/1705.08142)

