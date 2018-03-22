---
layout: post
title: "Inference in Probabilistic Graphical Models by Graph Neural Networks"
date: 2018-03-21 01:09:07
categories: arXiv_AI
tags: arXiv_AI Inference
author: KiJung Yoon, Renjie Liao, Yuwen Xiong, Lisa Zhang, Ethan Fetaya, Raquel Urtasun, Richard Zemel, Xaq Pitkow
mathjax: true
---

* content
{:toc}

##### Abstract
A useful computation when acting in a complex environment is to infer the marginal probabilities or most probable states of task-relevant variables. Probabilistic graphical models can efficiently represent the structure of such complex data, but performing these inferences is generally difficult. Message-passing algorithms, such as belief propagation, are a natural way to disseminate evidence amongst correlated variables while exploiting the graph structure, but these algorithms can struggle when the conditional dependency graphs contain loops. Here we use Graph Neural Networks (GNNs) to learn a message-passing algorithm that solves these inference tasks. We first show that the architecture of GNNs is well-matched to inference tasks. We then demonstrate the efficacy of this inference approach by training GNNs on an ensemble of graphical models and showing that they substantially outperform belief propagation on loopy graphs. Our message-passing algorithms generalize out of the training set to larger graphs and graphs with different structure.

##### Abstract (translated by Google)
在复杂环境中行事时的有用计算是推断任务相关变量的边际概率或最可能的状态。概率图形模型可以有效地表示这些复杂数据的结构，但执行这些推理通常很困难。信息传递算法（如信念传播）是利用图结构在相关变量之间传播证据的一种自然方式，但是当条件依赖图包含循环时，这些算法会很困难。在这里，我们使用图形神经网络（GNN）来学习解决这些推理任务的消息传递算法。我们首先表明，GNN的架构与推理任务是完全匹配的。然后，我们通过在图形模型集合上训练GNN来证明这种推理方法的有效性，并显示它们在loopy图表上大大优于信念传播。我们的消息传递算法将训练集推广到具有不同结构的更大的图和图。

##### URL
[http://arxiv.org/abs/1803.07710](http://arxiv.org/abs/1803.07710)

##### PDF
[http://arxiv.org/pdf/1803.07710](http://arxiv.org/pdf/1803.07710)

