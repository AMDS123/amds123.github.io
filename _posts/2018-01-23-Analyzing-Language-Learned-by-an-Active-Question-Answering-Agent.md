---
layout: post
title: "Analyzing Language Learned by an Active Question Answering Agent"
date: 2018-01-23 13:50:11
categories: arXiv_AI
tags: arXiv_AI QA Reinforcement_Learning
author: Christian Buck, Jannis Bulian, Massimiliano Ciaramita, Wojciech Gajewski, Andrea Gesmundo, Neil Houlsby, Wei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We analyze the language learned by an agent trained with reinforcement learning as a component of the ActiveQA system [Buck et al., 2017]. In ActiveQA, question answering is framed as a reinforcement learning task in which an agent sits between the user and a black box question-answering system. The agent learns to reformulate the user's questions to elicit the optimal answers. It probes the system with many versions of a question that are generated via a sequence-to-sequence question reformulation model, then aggregates the returned evidence to find the best answer. This process is an instance of \emph{machine-machine} communication. The question reformulation model must adapt its language to increase the quality of the answers returned, matching the language of the question answering system. We find that the agent does not learn transformations that align with semantic intuitions but discovers through learning classical information retrieval techniques such as tf-idf re-weighting and stemming.

##### Abstract (translated by Google)
我们分析了作为ActiveQA系统组成部分的受强化学习训练的代理学习的语言[Buck等，2017]。在ActiveQA中，问题回答被定义为一个强化学习任务，其中一个坐席位于用户和黑匣子问答系统之间。代理学会重新构造用户的问题以获得最佳答案。它通过序列到序列问题重构模型生成问题的多个版本，然后汇总返回的证据以找到最佳答案。这个过程是\ emph {machine-machine}通信的一个实例。问题重构模型必须适应其语言，以提高答案的质量，与问答系统的语言相匹配。我们发现代理不学习符合语义直觉的转换，而是通过学习经典的信息检索技术，如tf-idf的加权和词干来发现。

##### URL
[http://arxiv.org/abs/1801.07537](http://arxiv.org/abs/1801.07537)

##### PDF
[http://arxiv.org/pdf/1801.07537](http://arxiv.org/pdf/1801.07537)

