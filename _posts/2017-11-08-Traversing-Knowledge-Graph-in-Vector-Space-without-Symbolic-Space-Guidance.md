---
layout: post
title: "Traversing Knowledge Graph in Vector Space without Symbolic Space Guidance"
date: 2017-11-08 18:59:19
categories: arXiv_CL
tags: arXiv_CL Knowledge_Graph Knowledge Embedding Relation
author: Yelong Shen, Po-Sen Huang, Ming-Wei Chang, Jianfeng Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies on knowledge base completion, the task of recovering missing facts based on observed facts, demonstrate the importance of learning embeddings from multi-step relations. Due to the size of knowledge bases, previous works manually design relation paths of observed triplets in symbolic space (e.g. random walk) to learn multi-step relations during training. However, these approaches suffer some limitations as most paths are not informative, and it is prohibitively expensive to consider all possible paths. To address the limitations, we propose learning to traverse in vector space directly without the need of symbolic space guidance. To remember the connections between related observed triplets and be able to adaptively change relation paths in vector space, we propose Implicit ReasoNets (IRNs), that is composed of a global memory and a controller module to learn multi-step relation paths in vector space and infer missing facts jointly without any human-designed procedure. Without using any axillary information, our proposed model achieves state-of-the-art results on popular knowledge base completion benchmarks.

##### Abstract (translated by Google)
最近关于知识库完成的研究，基于观察到的事实恢复缺失事实的任务，表明了从多步关系中学习嵌入的重要性。由于知识库的大小，以前的工作是在符号空间（如随机游走）中手工设计观察三元组的关系路径，以在训练过程中学习多步关系。然而，这些方法受到一些限制，因为大多数路径不具有信息性，考虑所有可能的路径是昂贵的。为了解决这些限制，我们提出了学习直接在向量空间中进行遍历，而不需要象征性的空间引导。为了记住相关观测三元组之间的关系，并能够自适应地改变向量空间中的关系路径，我们提出了隐式重构网络（IRNs），它由全局存储器和控制器模块组成，以学习向量空间中的多步关系路径，在没有任何人为设计的程序下共同推断缺失的事实在不使用任何腋窝信息的情况下，我们提出的模型在流行的知识库完成基准上达到了最新的结果。

##### URL
[https://arxiv.org/abs/1611.04642](https://arxiv.org/abs/1611.04642)

##### PDF
[https://arxiv.org/pdf/1611.04642](https://arxiv.org/pdf/1611.04642)

