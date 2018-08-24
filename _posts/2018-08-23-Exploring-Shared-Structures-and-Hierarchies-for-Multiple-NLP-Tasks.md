---
layout: post
title: "Exploring Shared Structures and Hierarchies for Multiple NLP Tasks"
date: 2018-08-23 08:07:44
categories: arXiv_AI
tags: arXiv_AI Knowledge Text_Classification Reinforcement_Learning Classification
author: Junkun Chen, Kaiyu Chen, Xinchi Chen, Xipeng Qiu, Xuanjing Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Designing shared neural architecture plays an important role in multi-task learning. The challenge is that finding an optimal sharing scheme heavily relies on the expert knowledge and is not scalable to a large number of diverse tasks. Inspired by the promising work of neural architecture search (NAS), we apply reinforcement learning to automatically find possible shared architecture for multi-task learning. Specifically, we use a controller to select from a set of shareable modules and assemble a task-specific architecture, and repeat the same procedure for other tasks. The controller is trained with reinforcement learning to maximize the expected accuracies for all tasks. We conduct extensive experiments on two types of tasks, text classification and sequence labeling, which demonstrate the benefits of our approach.

##### Abstract (translated by Google)
设计共享神经结构在多任务学习中起着重要作用。挑战在于，找到最佳共享方案在很大程度上依赖于专业知识，并且无法扩展到大量不同的任务。受到神经架构搜索（NAS）的有前途的工作的启发，我们应用强化学习来自动找到可用于多任务学习的共享架构。具体来说，我们使用控制器从一组可共享模块中进行选择，并组装特定于任务的体系结构，并为其他任务重复相同的过程。控制器通过强化学习进行训练，以最大化所有任务的预期精度。我们对两类任务进行了广泛的实验，文本分类和序列标记，这些任务证明了我们的方法的好处。

##### URL
[http://arxiv.org/abs/1808.07658](http://arxiv.org/abs/1808.07658)

##### PDF
[http://arxiv.org/pdf/1808.07658](http://arxiv.org/pdf/1808.07658)

