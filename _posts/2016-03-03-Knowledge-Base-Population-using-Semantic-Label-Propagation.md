---
layout: post
title: "Knowledge Base Population using Semantic Label Propagation"
date: 2016-03-03 11:52:14
categories: arXiv_CL
tags: arXiv_CL Knowledge Relation
author: Lucas Sterckx, Thomas Demeester, Johannes Deleu, Chris Develder
mathjax: true
---

* content
{:toc}

##### Abstract
A crucial aspect of a knowledge base population system that extracts new facts from text corpora, is the generation of training data for its relation extractors. In this paper, we present a method that maximizes the effectiveness of newly trained relation extractors at a minimal annotation cost. Manual labeling can be significantly reduced by Distant Supervision, which is a method to construct training data automatically by aligning a large text corpus with an existing knowledge base of known facts. For example, all sentences mentioning both 'Barack Obama' and 'US' may serve as positive training instances for the relation born_in(subject,object). However, distant supervision typically results in a highly noisy training set: many training sentences do not really express the intended relation. We propose to combine distant supervision with minimal manual supervision in a technique called feature labeling, to eliminate noise from the large and noisy initial training set, resulting in a significant increase of precision. We further improve on this approach by introducing the Semantic Label Propagation method, which uses the similarity between low-dimensional representations of candidate training instances, to extend the training set in order to increase recall while maintaining high precision. Our proposed strategy for generating training data is studied and evaluated on an established test collection designed for knowledge base population tasks. The experimental results show that the Semantic Label Propagation strategy leads to substantial performance gains when compared to existing approaches, while requiring an almost negligible manual annotation effort.

##### Abstract (translated by Google)
从文本语料库中提取新事实的知识库人口系统的一个关键方面是为其关系提取器生成训练数据。在本文中，我们提出一种方法，以最小的注释成本最大化新训练的关系提取器的有效性。远程监督可以显着降低手动标记，这是一种通过将大型文本语料库与已知事实的现有知识库对齐来自动构建培训数据的方法。例如，所有提及“奥巴马”和“美国”的句子都可以作为正面的训练实例，用于出生（主体，客体）关系。然而，远程监督通常导致高度嘈杂的训练集：许多训练句并不真正表达预期的关系。我们建议在一种称为特征标记的技术中，将远程监督与最少的人工监督相结合，以消除来自大而有噪声的初始训练集合的噪声，从而显着提高精度。通过引入语义标签传播方法，利用候选训练实例的低维表示之间的相似性来扩展训练集以增加回忆，同时保持高精度，进一步改进了这种方法。我们提出的生成训练数据的策略是在为知识库人口任务设计的已建立的测试集上进行研究和评估的。实验结果表明，与现有方法相比，语义标签传播策略带来了显着的性能提升，同时需要几乎可以忽略的手动注释工作。

##### URL
[https://arxiv.org/abs/1511.06219](https://arxiv.org/abs/1511.06219)

##### PDF
[https://arxiv.org/pdf/1511.06219](https://arxiv.org/pdf/1511.06219)

