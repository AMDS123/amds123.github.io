---
layout: post
title: "R$^3$: Reinforced Reader-Ranker for Open-Domain Question Answering"
date: 2017-11-21 16:38:30
categories: arXiv_CL
tags: arXiv_CL QA Reinforcement_Learning
author: Shuohang Wang, Mo Yu, Xiaoxiao Guo, Zhiguo Wang, Tim Klinger, Wei Zhang, Shiyu Chang, Gerald Tesauro, Bowen Zhou, Jing Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years researchers have achieved considerable success applying neural network methods to question answering (QA). These approaches have achieved state of the art results in simplified closed-domain settings such as the SQuAD (Rajpurkar et al., 2016) dataset, which provides a pre-selected passage, from which the answer to a given question may be extracted. More recently, researchers have begun to tackle open-domain QA, in which the model is given a question and access to a large corpus (e.g., wikipedia) instead of a pre-selected passage (Chen et al., 2017a). This setting is more complex as it requires large-scale search for relevant passages by an information retrieval component, combined with a reading comprehension model that "reads" the passages to generate an answer to the question. Performance in this setting lags considerably behind closed-domain performance. In this paper, we present a novel open-domain QA system called Reinforced Ranker-Reader $(R^3)$, based on two algorithmic innovations. First, we propose a new pipeline for open-domain QA with a Ranker component, which learns to rank retrieved passages in terms of likelihood of generating the ground-truth answer to a given question. Second, we propose a novel method that jointly trains the Ranker along with an answer-generation Reader model, based on reinforcement learning. We report extensive experimental results showing that our method significantly improves on the state of the art for multiple open-domain QA datasets.

##### Abstract (translated by Google)
近年来，研究人员在神经网络方法应用于问答（QA）方面取得了相当大的成功。这些方法已经在简化的封闭域设置（诸如SQuAD（Rajpurkar等，2016）数据集）中实现了最新的结果，该数据集提供了预先选择的段落，从中可以提取给定问题的答案。最近，研究人员已经开始处理开放领域的质量保证问题，在这个问题中，模型被给出了一个问题，并且获得了一个庞大的语料库（例如维基百科），而不是预先选定的一段（Chen等，2017a）。这个设置更为复杂，因为它需要信息检索部分大规模地搜索相关段落，并结合阅读理解模型来“读取”段落以生成问题的答案。这种设置的性能远远落后于封闭域的性能。在本文中，我们提出了一种基于两种算法创新的新型开放域QA系统，称为增强型排序器（Reader）$（R ^ 3）$。首先，我们提出了一个新的带有Ranker组件的开放域QA流水线，该流水线学习根据对给定问题产生地面实况答案的可能性来对检索到的段落进行排名。其次，我们提出了一个新的方法，联合训练Ranker和一个基于强化学习的答案代阅读器模型。我们报告了广泛的实验结果，显示我们的方法显着提高了多个开放域QA数据集的最新技术水平。

##### URL
[https://arxiv.org/abs/1709.00023](https://arxiv.org/abs/1709.00023)

##### PDF
[https://arxiv.org/pdf/1709.00023](https://arxiv.org/pdf/1709.00023)

