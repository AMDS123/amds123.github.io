---
layout: post
title: "Represent, Aggregate, and Constrain: A Novel Architecture for Machine Reading from Noisy Sources"
date: 2016-10-30 22:33:47
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference
author: Jason Naradowsky, Sebastian Riedel
mathjax: true
---

* content
{:toc}

##### Abstract
In order to extract event information from text, a machine reading model must learn to accurately read and interpret the ways in which that information is expressed. But it must also, as the human reader must, aggregate numerous individual value hypotheses into a single coherent global analysis, applying global constraints which reflect prior knowledge of the domain. In this work we focus on the task of extracting plane crash event information from clusters of related news articles whose labels are derived via distant supervision. Unlike previous machine reading work, we assume that while most target values will occur frequently in most clusters, they may also be missing or incorrect. We introduce a novel neural architecture to explicitly model the noisy nature of the data and to deal with these aforementioned learning issues. Our models are trained end-to-end and achieve an improvement of more than 12.1 F$_1$ over previous work, despite using far less linguistic annotation. We apply factor graph constraints to promote more coherent event analyses, with belief propagation inference formulated within the transitions of a recurrent neural network. We show this technique additionally improves maximum F$_1$ by up to 2.8 points, resulting in a relative improvement of $50\%$ over the previous state-of-the-art.

##### Abstract (translated by Google)
为了从文本中提取事件信息，机器阅读模型必须学会准确地阅读和解释表达信息的方式。但是，正如人类读者所必须的那样，它也必须将许多单独的价值假设聚合成一个连贯的全局分析，应用反映该领域先验知识的全局约束。在这项工作中，我们把重点放在从相关新闻文章的集群中提取飞机坠毁事件信息的任务。与之前的机器阅读工作不同，我们假设尽管大多数目标值在大多数群集中会频繁出现，但也可能会丢失或不正确。我们引入了一种新的神经架构来明确地模拟数据的噪声性质，并处理上述的学习问题。我们的模型是端对端的培训，比以前的工作改进了12.1 F $ _1 $，尽管使用的语言注释少得多。我们应用因子图约束来促进更一致的事件分析，并在回归神经网络的转换中制定信念传播推论。我们展示了这种技术，最多可以将最高F $ _1 $提高2.8个百分点，比之前的技术水平提高了50％。

##### URL
[https://arxiv.org/abs/1610.09722](https://arxiv.org/abs/1610.09722)

##### PDF
[https://arxiv.org/pdf/1610.09722](https://arxiv.org/pdf/1610.09722)

