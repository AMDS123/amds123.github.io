---
layout: post
title: "Simple Recurrent Units for Highly Parallelizable Recurrence"
date: 2018-09-07 17:17:02
categories: arXiv_CL
tags: arXiv_CL CNN RNN Classification
author: Tao Lei, Yu Zhang, Sida I. Wang, Hui Dai, Yoav Artzi
mathjax: true
---

* content
{:toc}

##### Abstract
Common recurrent neural architectures scale poorly due to the intrinsic difficulty in parallelizing their state computations. In this work, we propose the Simple Recurrent Unit (SRU), a light recurrent unit that balances model capacity and scalability. SRU is designed to provide expressive recurrence, enable highly parallelized implementation, and comes with careful initialization to facilitate training of deep models. We demonstrate the effectiveness of SRU on multiple NLP tasks. SRU achieves 5--9x speed-up over cuDNN-optimized LSTM on classification and question answering datasets, and delivers stronger results than LSTM and convolutional models. We also obtain an average of 0.7 BLEU improvement over the Transformer model on translation by incorporating SRU into the architecture.

##### Abstract (translated by Google)
由于并行化状态计算的内在困难，常见的复现神经架构规模很小。在这项工作中，我们提出了简单循环单元（SRU），这是一种轻复数单元，可以平衡模型容量和可扩展性。 SRU旨在提供表达性重现，实现高度并行化的实现，并且需要仔细初始化以便于深度模型的训练。我们证明了SRU对多个NLP任务的有效性。 SRU在分类和问答数据集上比cuDNN优化的LSTM实现了5--9倍的加速，并且比LSTM和卷积模型提供更强的结果。通过将SRU结合到架构中，我们还获得了平均翻译的Transformer模型的平均0.7 BLEU。

##### URL
[http://arxiv.org/abs/1709.02755](http://arxiv.org/abs/1709.02755)

##### PDF
[http://arxiv.org/pdf/1709.02755](http://arxiv.org/pdf/1709.02755)

