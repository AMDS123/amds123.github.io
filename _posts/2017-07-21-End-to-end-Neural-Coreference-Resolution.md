---
layout: post
title: "End-to-end Neural Coreference Resolution"
date: 2017-07-21 21:05:04
categories: arXiv_CL
tags: arXiv_CL Object_Detection Attention Embedding Detection
author: Kenton Lee, Luheng He, Mike Lewis, Luke Zettlemoyer
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the first end-to-end coreference resolution model and show that it significantly outperforms all previous work without using a syntactic parser or hand-engineered mention detector. The key idea is to directly consider all spans in a document as potential mentions and learn distributions over possible antecedents for each. The model computes span embeddings that combine context-dependent boundary representations with a head-finding attention mechanism. It is trained to maximize the marginal likelihood of gold antecedent spans from coreference clusters and is factored to enable aggressive pruning of potential mentions. Experiments demonstrate state-of-the-art performance, with a gain of 1.5 F1 on the OntoNotes benchmark and by 3.1 F1 using a 5-model ensemble, despite the fact that this is the first approach to be successfully trained with no external resources.

##### Abstract (translated by Google)
我们引入了第一个端到端的共参与解决方案模型，并且显示出它在不使用句法分析器或手工设计的提及检测器的情况下显着优于以前的所有工作。关键的想法是直接考虑文档中的所有跨度作为潜在的提及，并学习可能的前提分布。该模型计算跨度嵌入，将上下文相关边界表示与头部寻找关注机制相结合。它被训练以最大化边际可能性的黄金先行跨度从联合集群，并考虑到积极修剪的潜在提及。实验证明了最先进的性能，在OntoNotes基准测试中获得了1.5 F1的成绩，而使用5模型合奏的成绩为3.1 F1，尽管事实上这是第一个没有外部资源的成功训练方法。

##### URL
[https://arxiv.org/abs/1707.07045](https://arxiv.org/abs/1707.07045)

##### PDF
[https://arxiv.org/pdf/1707.07045](https://arxiv.org/pdf/1707.07045)

