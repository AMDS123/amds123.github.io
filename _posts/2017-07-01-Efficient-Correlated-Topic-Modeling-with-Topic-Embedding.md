---
layout: post
title: "Efficient Correlated Topic Modeling with Topic Embedding"
date: 2017-07-01 21:10:15
categories: arXiv_CL
tags: arXiv_CL Embedding Inference Classification Relation
author: Junxian He, Zhiting Hu, Taylor Berg-Kirkpatrick, Ying Huang, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Correlated topic modeling has been limited to small model and problem sizes due to their high computational cost and poor scaling. In this paper, we propose a new model which learns compact topic embeddings and captures topic correlations through the closeness between the topic vectors. Our method enables efficient inference in the low-dimensional embedding space, reducing previous cubic or quadratic time complexity to linear w.r.t the topic size. We further speedup variational inference with a fast sampler to exploit sparsity of topic occurrence. Extensive experiments show that our approach is capable of handling model and data scales which are several orders of magnitude larger than existing correlation results, without sacrificing modeling quality by providing competitive or superior performance in document classification and retrieval.

##### Abstract (translated by Google)
相关主题建模由于计算成本高和缩放性差而一直限于小型模型和问题规模。在本文中，我们提出了一个新的模型，学习紧凑的主题嵌入，并通过主题向量之间的紧密性捕捉主题相关性。我们的方法能够在低维嵌入空间中进行高效的推理，将之前的三次或二次时间复杂度降低到主题大小的线性。我们进一步加快与快速采样器的变分推理，以利用主题发生的稀疏性。大量的实验表明，我们的方法能够处理比现有相关结果大几个数量级的模型和数据尺度，而不会通过在文档分类和检索中提供有竞争力的或优越的性能来牺牲建模质量。

##### URL
[https://arxiv.org/abs/1707.00206](https://arxiv.org/abs/1707.00206)

##### PDF
[https://arxiv.org/pdf/1707.00206](https://arxiv.org/pdf/1707.00206)

