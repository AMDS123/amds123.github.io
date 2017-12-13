---
layout: post
title: "Memory Augmented Neural Networks with Wormhole Connections"
date: 2017-01-30 17:34:51
categories: arXiv_CV
tags: arXiv_CV Embedding RNN Relation
author: Caglar Gulcehre, Sarath Chandar, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Recent empirical results on long-term dependency tasks have shown that neural networks augmented with an external memory can learn the long-term dependency tasks more easily and achieve better generalization than vanilla recurrent neural networks (RNN). We suggest that memory augmented neural networks can reduce the effects of vanishing gradients by creating shortcut (or wormhole) connections. Based on this observation, we propose a novel memory augmented neural network model called TARDIS (Temporal Automatic Relation Discovery in Sequences). The controller of TARDIS can store a selective set of embeddings of its own previous hidden states into an external memory and revisit them as and when needed. For TARDIS, memory acts as a storage for wormhole connections to the past to propagate the gradients more effectively and it helps to learn the temporal dependencies. The memory structure of TARDIS has similarities to both Neural Turing Machines (NTM) and Dynamic Neural Turing Machines (D-NTM), but both read and write operations of TARDIS are simpler and more efficient. We use discrete addressing for read/write operations which helps to substantially to reduce the vanishing gradient problem with very long sequences. Read and write operations in TARDIS are tied with a heuristic once the memory becomes full, and this makes the learning problem simpler when compared to NTM or D-NTM type of architectures. We provide a detailed analysis on the gradient propagation in general for MANNs. We evaluate our models on different long-term dependency tasks and report competitive results in all of them.

##### Abstract (translated by Google)
最近关于长期依赖性任务的实证结果表明，用外部记忆增强的神经网络可以更容易地学习长期依赖性任务，并且比香草递归神经网络（RNN）更容易实现更好的泛化。我们建议记忆增强神经网络可以通过创建快捷方式（或虫洞）连接来减少消失梯度的影响。基于这一观察，我们提出了一种称为TARDIS（序列中的时间自动关联发现）的新型记忆增广神经网络模型。 TARDIS的控制器可以将自己以前隐藏状态的选择性嵌套存储到外部存储器中，并在需要时重新访问它们。对于TARDIS来说，内存充当了过去的虫洞连接的存储器，可以更有效地传播渐变，并有助于学习时态依赖关系。 TARDIS的存储结构与神经图灵机（NTM）和动态神经图灵机（D-NTM）都有相似之处，但TARDIS的读写操作更为简单，效率更高。我们使用离散寻址进行读/写操作，这有助于大大减少非常长序列的消失梯度问题。一旦内存变满，TARDIS中的读写操作就与启发式相关联，与NTM或D-NTM类型的体系结构相比，这使得学习问题变得更简单。我们对MANNs的梯度传播进行了详细的分析。我们根据不同的长期依赖性任务评估我们的模型，并报告所有这些模型的竞争结果。

##### URL
[https://arxiv.org/abs/1701.08718](https://arxiv.org/abs/1701.08718)

##### PDF
[https://arxiv.org/pdf/1701.08718](https://arxiv.org/pdf/1701.08718)

