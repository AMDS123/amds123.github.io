---
layout: post
title: "Knowledge-Guided Recurrent Neural Network Learning for Task-Oriented Action Prediction"
date: 2017-07-15 01:40:07
categories: arXiv_CV
tags: arXiv_CV Knowledge RNN Prediction
author: Liang Lin, Lili Huang, Tianshui Chen, Yukang Gan, Hui Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims at task-oriented action prediction, i.e., predicting a sequence of actions towards accomplishing a specific task under a certain scene, which is a new problem in computer vision research. The main challenges lie in how to model task-specific knowledge and integrate it in the learning procedure. In this work, we propose to train a recurrent long-short term memory (LSTM) network for handling this problem, i.e., taking a scene image (including pre-located objects) and the specified task as input and recurrently predicting action sequences. However, training such a network usually requires large amounts of annotated samples for covering the semantic space (e.g., diverse action decomposition and ordering). To alleviate this issue, we introduce a temporal And-Or graph (AOG) for task description, which hierarchically represents a task into atomic actions. With this AOG representation, we can produce many valid samples (i.e., action sequences according with common sense) by training another auxiliary LSTM network with a small set of annotated samples. And these generated samples (i.e., task-oriented action sequences) effectively facilitate training the model for task-oriented action prediction. In the experiments, we create a new dataset containing diverse daily tasks and extensively evaluate the effectiveness of our approach.

##### Abstract (translated by Google)
本文针对面向任务的动作预测，即预测在特定场景下完成特定任务的一系列动作，这是计算机视觉研究中的一个新问题。主要的挑战在于如何对特定任务的知识进行建模并将其融入到学习过程中。在这项工作中，我们建议训练一个经常性的长期记忆（LSTM）网络来处理这个问题，即将一个场景图像（包括预定位的对象）和指定的任务作为输入，并且反复地预测动作序列。然而，训练这样的网络通常需要大量的注释样本来覆盖语义空间（例如，不同的动作分解和排序）。为了缓解这个问题，我们引入了一个任务描述的时间和 - 图（AOG），它将任务分层次地表示为原子动作。利用这个AOG表示，我们可以通过训练具有少量注释样本的辅助LSTM网络来产生许多有效样本（即，根据常识的动作序列）。这些生成的样本（即面向任务的动作序列）有效地促进了面向任务动作预测的模型的训练。在实验中，我们创建了一个包含各种日常任务的新数据集，并广泛评估了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1707.04677](https://arxiv.org/abs/1707.04677)

##### PDF
[https://arxiv.org/pdf/1707.04677](https://arxiv.org/pdf/1707.04677)

