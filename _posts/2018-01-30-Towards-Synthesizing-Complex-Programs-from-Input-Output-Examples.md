---
layout: post
title: "Towards Synthesizing Complex Programs from Input-Output Examples"
date: 2018-01-30 04:54:32
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning
author: Xinyun Chen, Chang Liu, Dawn Song
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep learning techniques have been developed to improve the performance of program synthesis from input-output examples. Albeit its significant progress, the programs that can be synthesized by state-of-the-art approaches are still simple in terms of their complexity. In this work, we move a significant step forward along this direction by proposing a new class of challenging tasks in the domain of program synthesis from input-output examples: learning a context-free parser from pairs of input programs and their parse trees. We show that this class of tasks are much more challenging than previously studied tasks, and the test accuracy of existing approaches is almost 0%. 
 We tackle the challenges by developing three novel techniques inspired by three novel observations, which reveal the key ingredients of using deep learning to synthesize a complex program. First, the use of a non-differentiable machine is the key to effectively restrict the search space. Thus our proposed approach learns a neural program operating a domain-specific non-differentiable machine. Second, recursion is the key to achieve generalizability. Thus, we bake-in the notion of recursion in the design of our non-differentiable machine. Third, reinforcement learning is the key to learn how to operate the non-differentiable machine, but it is also hard to train the model effectively with existing reinforcement learning algorithms from a cold boot. We develop a novel two-phase reinforcement learning-based search algorithm to overcome this issue. In our evaluation, we show that using our novel approach, neural parsing programs can be learned to achieve 100% test accuracy on test inputs that are 500x longer than the training samples.

##### Abstract (translated by Google)
近年来，深度学习技术已经被开发出来，以提高程序综合的性能，从输入输出的例子。虽然它的重大进展，但是可以通过最先进的方法综合的方案在其复杂性方面仍然是简单的。在这项工作中，我们沿着这个方向前进了一大步，从输入输出的例子中提出了一个新的课程综合领域的具有挑战性的任务：从输入程序对和他们的分析树学习一个上下文无关的解析器。我们表明，这类任务比以前研究的任务更具挑战性，现有方法的测试准确性几乎为0％。
 我们通过开发三种新颖的技术来应对这些挑战，这些技术受到三种新颖观察的启发，揭示了使用深度学习来综合复杂程序的关键因素。首先，使用不可微机是有效限制搜索空间的关键。因此，我们提出的方法学习一个神经程序运行一个领域特定的非微分机器。其次，递归是实现泛化的关键。因此，我们烘烤了我们的不可微机器的设计中递归的概念。第三，强化学习是学习如何操作非微分机器的关键，但是现有的从冷启动强化学习算法难以有效地训练模型。我们开发了一个新颖的两阶段强化学习为基础的搜索算法来克服这个问题。在我们的评估中，我们展示了使用我们的新颖方法，可以学习神经解析程序，以在测试输入上达到100％的测试精度，这些测试输入比训练样本长500倍。

##### URL
[http://arxiv.org/abs/1706.01284](http://arxiv.org/abs/1706.01284)

##### PDF
[http://arxiv.org/pdf/1706.01284](http://arxiv.org/pdf/1706.01284)

