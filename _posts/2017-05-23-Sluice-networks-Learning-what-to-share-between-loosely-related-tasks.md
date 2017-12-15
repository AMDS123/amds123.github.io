---
layout: post
title: "Sluice networks: Learning what to share between loosely related tasks"
date: 2017-05-23 08:58:09
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Sebastian Ruder, Joachim Bingel, Isabelle Augenstein, Anders Søgaard
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task learning is partly motivated by the observation that humans bring to bear what they know about related problems when solving new ones. Similarly, deep neural networks can profit from related tasks by sharing parameters with other networks. However, humans do not consciously decide to transfer knowledge between tasks (and are typically not aware of the transfer). In machine learning, it is hard to estimate if sharing will lead to improvements; especially if tasks are only loosely related. To overcome this, we introduce Sluice Networks, a general framework for multi-task learning where trainable parameters control the amount of sharing -- including which parts of the models to share. Our framework goes beyond and generalizes over previous proposals in enabling hard or soft sharing of all combinations of subspaces, layers, and skip connections. We perform experiments on three task pairs from natural language processing, and across seven different domains, using data from OntoNotes 5.0, and achieve up to 15% average error reductions over common approaches to multi-task learning. We analyze when the architecture is particularly helpful, as well as its ability to fit noise. We show that a) label entropy is predictive of gains in sluice networks, confirming findings for hard parameter sharing, and b) while sluice networks easily fit noise, they are robust across domains in practice.

##### Abstract (translated by Google)
多任务学习的部分动机是观察到人类在解决新问题时带来的有关问题。同样，深度神经网络可以通过与其他网络共享参数从相关任务中获益。然而，人类不会有意识地决定在任务之间转移知识（并且通常不知道转移）。在机器学习中，很难估计共享是否会导致改进;特别是如果任务只是松散的相关。为了克服这个问题，我们介绍Sluice Networks，一个多任务学习的通用框架，其中可训练参数控制共享的数量，包括共享模型的哪一部分。我们的框架超越了以前的提议，使得子空间，图层和跳过连接的所有组合都能够硬共享或软共享。我们使用来自OntoNotes 5.0的数据对来自自然语言处理的三个任务对以及跨越七个不同领域的实验进行实验，并且与通常的多任务学习方法相比，平均错误减少达到15％。我们分析这个架构何时特别有用，以及它适合噪声的能力。我们表明：a）标签熵是预测水闸网络中的增益，确认硬参数共享的结果; b）水闸网络容易适应噪声，它们在实践中跨域强健。

##### URL
[https://arxiv.org/abs/1705.08142](https://arxiv.org/abs/1705.08142)

##### PDF
[https://arxiv.org/pdf/1705.08142](https://arxiv.org/pdf/1705.08142)

