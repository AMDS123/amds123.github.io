---
layout: post
title: "Building a Fine-Grained Entity Typing System Overnight for a New X"
date: 2016-03-10 00:33:28
categories: arXiv_SD
tags: arXiv_SD Knowledge Embedding Relation
author: Lifu Huang, Jonathan May, Xiaoman Pan, Heng Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Recent research has shown great progress on fine-grained entity typing. Most existing methods require pre-defining a set of types and training a multi-class classifier from a large labeled data set based on multi-level linguistic features. They are thus limited to certain domains, genres and languages. In this paper, we propose a novel unsupervised entity typing framework by combining symbolic and distributional semantics. We start from learning general embeddings for each entity mention, compose the embeddings of specific contexts using linguistic structures, link the mention to knowledge bases and learn its related knowledge representations. Then we develop a novel joint hierarchical clustering and linking algorithm to type all mentions using these representations. This framework doesn't rely on any annotated data, predefined typing schema, or hand-crafted features, therefore it can be quickly adapted to a new domain, genre and language. Furthermore, it has great flexibility at incorporating linguistic structures (e.g., Abstract Meaning Representation (AMR), dependency relations) to improve specific context representation. Experiments on genres (news and discussion forum) show comparable performance with state-of-the-art supervised typing systems trained from a large amount of labeled data. Results on various languages (English, Chinese, Japanese, Hausa, and Yoruba) and domains (general and biomedical) demonstrate the portability of our framework.

##### Abstract (translated by Google)
最近的研究已经在细粒度实体分类方面取得了很大进展。大多数现有的方法需要预先定义一组类型，并基于多级语言特征从大型标注数据集中训练多级分类器。因此，它们仅限于某些领域，流派和语言。在这篇文章中，我们提出了一个新颖的无监督的实体类型框架，结合了符号和分布式语义。我们从学习每个实体提到的通用嵌入开始，使用语言结构构建特定上下文的嵌入，将提及链接到知识库并学习其相关的知识表示。然后，我们开发一种新型的联合层次聚类和链接算法来使用这些表示来键入所有的提及。这个框架不依赖任何带注释的数据，预定义的输入模式或手工特征，因此可以快速适应新的领域，流派和语言。此外，在结合语言结构（例如，抽象意义表示（AMR），依赖关系）方面具有很大的灵活性以改善特定的上下文表示。流派的实验（新闻和论坛）显示了与大量标记数据训练的最先进的监督分类系统相当的性能。各种语言（英语，汉语，日语，豪撒语和约鲁巴语）和领域（普通语言和生物医学）的结果证明了我们框架的可移植性。

##### URL
[https://arxiv.org/abs/1603.03112](https://arxiv.org/abs/1603.03112)

##### PDF
[https://arxiv.org/pdf/1603.03112](https://arxiv.org/pdf/1603.03112)

