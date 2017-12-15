---
layout: post
title: "CoType: Joint Extraction of Typed Entities and Relations with Knowledge Bases"
date: 2017-06-02 19:28:19
categories: arXiv_CL
tags: arXiv_CL Knowledge Segmentation Relation_Extraction Embedding Optimization Relation
author: Xiang Ren, Zeqiu Wu, Wenqi He, Meng Qu, Clare R. Voss, Heng Ji, Tarek F. Abdelzaher, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting entities and relations for types of interest from text is important for understanding massive text corpora. Traditionally, systems of entity relation extraction have relied on human-annotated corpora for training and adopted an incremental pipeline. Such systems require additional human expertise to be ported to a new domain, and are vulnerable to errors cascading down the pipeline. In this paper, we investigate joint extraction of typed entities and relations with labeled data heuristically obtained from knowledge bases (i.e., distant supervision). As our algorithm for type labeling via distant supervision is context-agnostic, noisy training data poses unique challenges for the task. We propose a novel domain-independent framework, called CoType, that runs a data-driven text segmentation algorithm to extract entity mentions, and jointly embeds entity mentions, relation mentions, text features and type labels into two low-dimensional spaces (for entity and relation mentions respectively), where, in each space, objects whose types are close will also have similar representations. CoType, then using these learned embeddings, estimates the types of test (unlinkable) mentions. We formulate a joint optimization problem to learn embeddings from text corpora and knowledge bases, adopting a novel partial-label loss function for noisy labeled data and introducing an object "translation" function to capture the cross-constraints of entities and relations on each other. Experiments on three public datasets demonstrate the effectiveness of CoType across different domains (e.g., news, biomedical), with an average of 25% improvement in F1 score compared to the next best method.

##### Abstract (translated by Google)
从文本中提取感兴趣类型的实体和关系对于理解大量的文本语料很重要。传统上，实体关系抽取系统依靠人工注释语料进行训练，并采用增量管线。这样的系统需要额外的人力专长才能移植到一个新的领域，并且容易出现级联的错误。在本文中，我们调查联合提取类型的实体和与从知识库（即远程监督）启发式获得的标记数据的关系。由于我们通过远程监控进行类型标记的算法是与上下文无关的，所以嘈杂的训练数据给这项任务带来了独特的挑战。我们提出了一个新的与领域无关的框架，称为CoType，它运行一个数据驱动的文本分割算法来提取实体提及，并将实体提及，关系提及，文本特征和类型标签共同嵌入到两个低维空间关系分别提到），其中在每个空间中，类型相近的对象也将具有相似的表示。 CoType，然后使用这些学习的嵌入，估计测试类型（不可链接）的提及。我们制定了一个联合优化问题，从文本语料库和知识库中学习嵌入，采用新颖的部分标签损失函数来处理带噪标签的数据，引入对象“翻译”功能来捕捉实体和关系的交叉约束。三个公共数据集上的实验证明了CoType在不同领域（例如新闻，生物医学）的有效性，与下一个最佳方法相比，F1得分平均提高了25％。

##### URL
[https://arxiv.org/abs/1610.08763](https://arxiv.org/abs/1610.08763)

##### PDF
[https://arxiv.org/pdf/1610.08763](https://arxiv.org/pdf/1610.08763)

