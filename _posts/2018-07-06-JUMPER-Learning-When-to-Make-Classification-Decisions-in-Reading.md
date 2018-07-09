---
layout: post
title: "JUMPER: Learning When to Make Classification Decisions in Reading"
date: 2018-07-06 08:49:56
categories: arXiv_AI
tags: arXiv_AI Text_Classification Reinforcement_Learning Classification Prediction
author: Xianggen Liu, Lili Mou, Haotian Cui, Zhengdong Lu, Sen Song
mathjax: true
---

* content
{:toc}

##### Abstract
In early years, text classification is typically accomplished by feature-based machine learning models; recently, deep neural networks, as a powerful learning machine, make it possible to work with raw input as the text stands. However, exiting end-to-end neural networks lack explicit interpretation of the prediction. In this paper, we propose a novel framework, JUMPER, inspired by the cognitive process of text reading, that models text classification as a sequential decision process. Basically, JUMPER is a neural system that scans a piece of text sequentially and makes classification decisions at the time it wishes. Both the classification result and when to make the classification are part of the decision process, which is controlled by a policy network and trained with reinforcement learning. Experimental results show that a properly trained JUMPER has the following properties: (1) It can make decisions whenever the evidence is enough, therefore reducing total text reading by 30-40% and often finding the key rationale of prediction. (2) It achieves classification accuracy better than or comparable to state-of-the-art models in several benchmark and industrial datasets.

##### Abstract (translated by Google)
在早期，文本分类通常通过基于特征的机器学习模型来完成;最近，深度神经网络作为一种强大的学习机器，可以在文本中使用原始输入。然而，退出端到端神经网络缺乏对预测的明确解释。在本文中，我们提出了一个新的框架，JUMPER，受文本阅读的认知过程的启发，将文本分类建模为一个连续的决策过程。基本上，JUMPER是一个神经系统，它按顺序扫描一段文本，并在其希望的时候做出分类决定。分类结果和何时进行分类都是决策过程的一部分，由政策网络控制并通过强化学习进行培训。实验结果表明，经过适当训练的JUMPER具有以下特性：（1）只要证据充分，就可以做出决策，从而将总文本阅读量降低30-40％，并经常找到预测的关键理论基础。 （2）它在几个基准和工业数据集中实现了比最先进模型更好或更可比的分类精度。

##### URL
[http://arxiv.org/abs/1807.02314](http://arxiv.org/abs/1807.02314)

##### PDF
[http://arxiv.org/pdf/1807.02314](http://arxiv.org/pdf/1807.02314)

