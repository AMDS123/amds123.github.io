---
layout: post
title: "Question Answering over Freebase via Attentive RNN with Similarity Matrix based CNN"
date: 2018-05-27 13:36:15
categories: arXiv_AI
tags: arXiv_AI Knowledge QA Attention Embedding CNN RNN Detection Relation
author: Yingqi Qu, Jie Liu, Liangyi Kang, Qinfeng Shi, Dan Ye
mathjax: true
---

* content
{:toc}

##### Abstract
With the rapid growth of knowledge bases (KBs), question answering over knowledge base, a.k.a. KBQA has drawn huge attention in recent years. Most of the existing KBQA methods follow so called encoder-compare framework. They map the question and the KB facts to a common embedding space, in which the similarity between the question vector and the fact vectors can be conveniently computed. This, however, inevitably loses original words interaction information. To preserve more original information, we propose an attentive recurrent neural network with similarity matrix based convolutional neural network (AR-SMCNN) model, which is able to capture comprehensive hierarchical information utilizing the advantages of both RNN and CNN. We use RNN to capture semantic-level correlation by its sequential modeling nature, and use an attention mechanism to keep track of the entities and relations simultaneously. Meanwhile, we use a similarity matrix based CNN with two-directions pooling to extract literal-level words interaction matching utilizing CNNs strength of modeling spatial correlation among data. Moreover, we have developed a new heuristic extension method for entity detection, which significantly decreases the effect of noise. Our method has outperformed the state-of-the-arts on SimpleQuestion benchmark in both accuracy and efficiency.

##### Abstract (translated by Google)
随着知识库（Knowledge Base，KB）的快速增长，对知识库的回答问题也在近年来引起了人们的高度关注。大多数现有的KBQA方法都遵循所谓的编码器比较框架。他们将问题和知识库事实映射到一个共同的嵌入空间，其中问题向量和事实向量之间的相似性可以方便地计算出来。然而，这不可避免地会丢失原始单词交互信息。为了保留更多的原始信息，我们提出了一种基于相似矩阵的卷积神经网络模型（AR-SMCNN），该模型能够利用RNN和CNN两者的优势来捕获综合分层信息。我们使用RNN通过序列建模本质来捕获语义级关联，并使用注意机制同时跟踪实体和关系。同时，我们使用基于CNN的相似矩阵和双向池来提取字面级词语交互匹配，利用数据间建模空间相关性的CNN强度。此外，我们开发了一种新的实体检测启发式扩展方法，大大降低了噪声的影响。我们的方法在准确性和效率上都超越了SimpleQuestion基准测试的先进水平。

##### URL
[http://arxiv.org/abs/1804.03317](http://arxiv.org/abs/1804.03317)

##### PDF
[http://arxiv.org/e-print/1804.03317](http://arxiv.org/e-print/1804.03317)

