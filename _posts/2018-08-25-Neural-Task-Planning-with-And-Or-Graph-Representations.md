---
layout: post
title: "Neural Task Planning with And-Or Graph Representations"
date: 2018-08-25 02:57:23
categories: arXiv_CV
tags: arXiv_CV Knowledge RNN
author: Tianshui Chen, Riquan Chen, Lin Nie, Xiaonan Luo, Xiaobai Liu, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on semantic task planning, i.e., predicting a sequence of actions toward accomplishing a specific task under a certain scene, which is a new problem in computer vision research. The primary challenges are how to model task-specific knowledge and how to integrate this knowledge into the learning procedure. In this work, we propose training a recurrent long short-term memory (LSTM) network to address this problem, i.e., taking a scene image (including pre-located objects) and the specified task as input and recurrently predicting action sequences. However, training such a network generally requires large numbers of annotated samples to cover the semantic space (e.g., diverse action decomposition and ordering). To overcome this issue, we introduce a knowledge and-or graph (AOG) for task description, which hierarchically represents a task as atomic actions. With this AOG representation, we can produce many valid samples (i.e., action sequences according to common sense) by training another auxiliary LSTM network with a small set of annotated samples. Furthermore, these generated samples (i.e., task-oriented action sequences) effectively facilitate training of the model for semantic task planning. In our experiments, we create a new dataset that contains diverse daily tasks and extensively evaluate the effectiveness of our approach.

##### Abstract (translated by Google)
本文重点研究语义任务规划，即预测在某一场景下完成特定任务的一系列动作，这是计算机视觉研究中的一个新问题。主要挑战是如何建模任务特定知识以及如何将这些知识整合到学习过程中。在这项工作中，我们建议训练一个循环长期短期记忆（LSTM）网络来解决这个问题，即将场景图像（包括预先定位的对象）和指定的任务作为输入并反复预测动作序列。然而，训练这样的网络通常需要大量注释的样本来覆盖语义空间（例如，不同的动作分解和排序）。为了克服这个问题，我们引入了一个用于任务描述的知识和/或图形（AOG），它将一个任务分层地表示为原子动作。利用这种AOG表示，我们可以通过训练具有一小组注释样本的另一个辅助LSTM网络来产生许多有效样本（即，根据常识的动作序列）。此外，这些生成的样本（即，面向任务的动作序列）有效地促进了用于语义任务规划的模型的训练。在我们的实验中，我们创建了一个包含各种日常任务的新数据集，并广泛评估了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1808.09284](http://arxiv.org/abs/1808.09284)

##### PDF
[http://arxiv.org/pdf/1808.09284](http://arxiv.org/pdf/1808.09284)

