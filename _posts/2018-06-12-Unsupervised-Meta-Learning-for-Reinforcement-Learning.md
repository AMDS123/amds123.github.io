---
layout: post
title: "Unsupervised Meta-Learning for Reinforcement Learning"
date: 2018-06-12 16:48:52
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Abhishek Gupta, Benjamin Eysenbach, Chelsea Finn, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Meta-learning is a powerful tool that builds on multi-task learning to learn how to quickly adapt a model to new tasks. In the context of reinforcement learning, meta-learning algorithms can acquire reinforcement learning procedures to solve new problems more efficiently by meta-learning prior tasks. The performance of meta-learning algorithms critically depends on the tasks available for meta-training: in the same way that supervised learning algorithms generalize best to test points drawn from the same distribution as the training points, meta-learning methods generalize best to tasks from the same distribution as the meta-training tasks. In effect, meta-reinforcement learning offloads the design burden from algorithm design to task design. If we can automate the process of task design as well, we can devise a meta-learning algorithm that is truly automated. In this work, we take a step in this direction, proposing a family of unsupervised meta-learning algorithms for reinforcement learning. We describe a general recipe for unsupervised meta-reinforcement learning, and describe an effective instantiation of this approach based on a recently proposed unsupervised exploration technique and model-agnostic meta-learning. We also discuss practical and conceptual considerations for developing unsupervised meta-learning methods. Our experimental results demonstrate that unsupervised meta-reinforcement learning effectively acquires accelerated reinforcement learning procedures without the need for manual task design, significantly exceeds the performance of learning from scratch, and even matches performance of meta-learning methods that use hand-specified task distributions.

##### Abstract (translated by Google)
元学习是一个强大的工具，建立在多任务学习的基础上，学习如何快速地将模型适应新的任务。在强化学习的背景下，元学习算法可以通过元学习先验任务获得强化学习过程以更有效地解决新问题。元学习算法的性能主要取决于元训练的可用任务：就像监督学习算法一般最好地推广测试与训练点相同分布的点一样，元学习方法最适合从与元训练任务相同的分配。实际上，元强化学习将设计负担从算法设计转移到任务设计。如果我们也可以自动完成任务设计过程，那么我们可以设计一个真正自动化的元学习算法。在这项工作中，我们朝这个方向迈出了一步，提出了一套用于强化学习的无监督元学习算法。我们描述了无监督元强化学习的一般配方，并描述了基于最近提出的无监督探索技术和模型不可知元学习的这种方法的有效实例。我们还讨论了开发无监督元学习方法的实际和概念上的考虑。我们的实验结果表明，无监督元强化学习有效地获得了加速强化学习过程，而无需手动任务设计，明显超过了从零开始学习的性能，甚至匹配使用手工指定任务分布的元学习方法的性能。

##### URL
[http://arxiv.org/abs/1806.04640](http://arxiv.org/abs/1806.04640)

##### PDF
[http://arxiv.org/pdf/1806.04640](http://arxiv.org/pdf/1806.04640)

