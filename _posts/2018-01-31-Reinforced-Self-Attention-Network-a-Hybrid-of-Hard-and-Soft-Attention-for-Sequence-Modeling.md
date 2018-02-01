---
layout: post
title: "Reinforced Self-Attention Network: a Hybrid of Hard and Soft Attention for Sequence Modeling"
date: 2018-01-31 04:30:32
categories: arXiv_CL
tags: arXiv_CL Sparse Knowledge Attention Inference RNN
author: Tao Shen, Tianyi Zhou, Guodong Long, Jing Jiang, Sen Wang, Chengqi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Many natural language processing tasks solely rely on sparse dependencies between a few tokens in a sentence. Soft attention mechanisms show promising performance in modeling local/global dependencies by soft probabilities between every two tokens, but they are not effective and efficient when applied to long sentences. By contrast, hard attention mechanisms directly select a subset of tokens but are difficult and inefficient to train due to their combinatorial nature. In this paper, we integrate both soft and hard attention into one context fusion model, "reinforced self-attention (ReSA)", for the mutual benefit of each other. In ReSA, a hard attention trims a sequence for a soft self-attention to process, while the soft attention feeds reward signals back to facilitate the training of the hard one. For this purpose, we develop a novel hard attention called "reinforced sequence sampling (RSS)", selecting tokens in parallel and trained via policy gradient. Using two RSS modules, ReSA efficiently extracts the sparse dependencies between each pair of selected tokens. We finally propose an RNN/CNN-free sentence-encoding model, "reinforced self-attention network (ReSAN)", solely based on ReSA. It achieves state-of-the-art performance on both Stanford Natural Language Inference (SNLI) and Sentences Involving Compositional Knowledge (SICK) datasets.

##### Abstract (translated by Google)
许多自然语言处理任务完全依赖于句子中的几个令牌之间的稀疏依赖关系。软注意机制在用两个令牌之间的软概率来建模局部/全局依赖性方面表现出有希望的性能，但是当应用于长句时，它们不是有效和高效的。相比之下，硬注意机制直接选择一个令牌的子集，但由于其组合性质，难以进行训练。在这篇论文中，我们将软硬两方面的注意力集中在一个上下文融合模型“增强自我注意力（ReSA）”上，以便彼此互利。在ReSA，一个注意力集中在一个软的自我注意过程的顺序上，而软性的注意力则回馈给回报的信号，以促进训练的困难。为此，我们开发了一个新的“加强序列采样（RSS）”的硬注意力，并行选择代币并通过策略梯度进行训练。使用两个RSS模块，ReSA可以高效地提取每对选定令牌之间的稀疏依赖关系。我们最终提出了一个仅基于ReSA的RNN / CNN句子编码模型，“增强型自我关注网络（ReSAN）”。它在斯坦福自然语言推理（SNLI）和涉及构成知识（SICK）数据集的句子上达到了最先进的性能。

##### URL
[http://arxiv.org/abs/1801.10296](http://arxiv.org/abs/1801.10296)

##### PDF
[http://arxiv.org/pdf/1801.10296](http://arxiv.org/pdf/1801.10296)

