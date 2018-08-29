---
layout: post
title: "A Unified Query-based Generative Model for Question Generation and Question Answering"
date: 2018-08-28 14:04:39
categories: arXiv_CL
tags: arXiv_CL QA Attention Reinforcement_Learning RNN
author: Linfeng Song, Zhiguo Wang, Wael Hamza
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a query-based generative model for solving both tasks of question generation (QG) and question an- swering (QA). The model follows the classic encoder- decoder framework. The encoder takes a passage and a query as input then performs query understanding by matching the query with the passage from multiple per- spectives. The decoder is an attention-based Long Short Term Memory (LSTM) model with copy and coverage mechanisms. In the QG task, a question is generated from the system given the passage and the target answer, whereas in the QA task, the answer is generated given the question and the passage. During the training stage, we leverage a policy-gradient reinforcement learning algorithm to overcome exposure bias, a major prob- lem resulted from sequence learning with cross-entropy loss. For the QG task, our experiments show higher per- formances than the state-of-the-art results. When used as additional training data, the automatically generated questions even improve the performance of a strong ex- tractive QA system. In addition, our model shows bet- ter performance than the state-of-the-art baselines of the generative QA task.

##### Abstract (translated by Google)
我们提出了一种基于查询的生成模型，用于解决问题生成（QG）和问题交换（QA）的任务。该模型遵循经典的编码器 - 解码器框架。编码器将一个段落和一个查询作为输入，然后通过将查询与来自多个视角的段落进行匹配来执行查询理解。解码器是基于注意力的长期短期记忆（LSTM）模型，具有复制和覆盖机制。在QG任务中，在给定通过和目标答案的情况下从系统生成问题，而在QA任务中，给出问题和段落生成答案。在培训阶段，我们利用政策梯度强化学习算法来克服暴露偏差，这是由交叉熵损失的序列学习引起的一个主要问题。对于QG任务，我们的实验显示出比最先进的结果更高的性能。当用作额外的训练数据时，自动生成的问题甚至可以改善强大的有效QA系统的性能。此外，我们的模型显示出比生成QA任务的最新基线更好的表现。

##### URL
[http://arxiv.org/abs/1709.01058](http://arxiv.org/abs/1709.01058)

##### PDF
[http://arxiv.org/pdf/1709.01058](http://arxiv.org/pdf/1709.01058)

