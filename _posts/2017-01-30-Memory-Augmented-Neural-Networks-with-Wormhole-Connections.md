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


##### URL
[https://arxiv.org/abs/1701.08718](https://arxiv.org/abs/1701.08718)

##### PDF
[https://arxiv.org/pdf/1701.08718](https://arxiv.org/pdf/1701.08718)

