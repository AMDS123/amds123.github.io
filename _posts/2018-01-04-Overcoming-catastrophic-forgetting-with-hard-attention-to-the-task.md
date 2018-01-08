---
layout: post
title: "Overcoming catastrophic forgetting with hard attention to the task"
date: 2018-01-04 16:22:22
categories: arXiv_AI
tags: arXiv_AI Knowledge Attention Gradient_Descent
author: Joan Serr&#xe0;, D&#xed;dac Sur&#xed;s, Marius Miron, Alexandros Karatzoglou
mathjax: true
---

* content
{:toc}

##### Abstract
Catastrophic forgetting occurs when a neural network loses the information learned with the first task, after training on a second task. This problem remains a hurdle for general artificial intelligence systems with sequential learning capabilities. In this paper, we propose a task-based hard attention mechanism that preserves previous tasks' information without substantially affecting the current task's learning. An attention mask is learned concurrently to every task through stochastic gradient descent, and previous masks are exploited to constrain such learning. We show that the proposed mechanism is effective for reducing catastrophic forgetting, cutting current rates by 33 to 84%. We also show that it is robust to different hyperparameter choices and that it offers a number of monitoring capabilities. The approach features the possibility to control both the stability and compactness of the learned knowledge, which we believe makes it also attractive for online learning and network compression applications.

##### Abstract (translated by Google)
灾难性遗忘发生在神经网络在第二项任务的训练之后失去了第一项任务学习的信息。这个问题仍然是具有顺序学习能力的一般人工智能系统的障碍。在本文中，我们提出了一个基于任务的注意力机制，它保留了以前的任务信息，而不会对当前任务的学习产生实质性的影响。通过随机梯度下降对每个任务同时学习注意掩码，并利用以前的掩码来约束这种学习。我们表明，提出的机制是有效的减少灾难性遗忘，削减目前的利率33至84％。我们还表明，它对于不同的超参数选择是强健的，它提供了许多监控功能。该方法的特点是可以控制学习知识的稳定性和紧凑性，我们认为这对于在线学习和网络压缩应用来说也是有吸引力的。

##### URL
[http://arxiv.org/abs/1801.01423](http://arxiv.org/abs/1801.01423)

##### PDF
[http://arxiv.org/pdf/1801.01423](http://arxiv.org/pdf/1801.01423)

