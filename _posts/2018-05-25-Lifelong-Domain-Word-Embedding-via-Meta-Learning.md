---
layout: post
title: "Lifelong Domain Word Embedding via Meta-Learning"
date: 2018-05-25 06:10:54
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Hu Xu, Bing Liu, Lei Shu, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Learning high-quality domain word embeddings is important for achieving good performance in many NLP tasks. General-purpose embeddings trained on large-scale corpora are often sub-optimal for domain-specific applications. However, domain-specific tasks often do not have large in-domain corpora for training high-quality domain embeddings. In this paper, we propose a novel lifelong learning setting for domain embedding. That is, when performing the new domain embedding, the system has seen many past domains, and it tries to expand the new in-domain corpus by exploiting the corpora from the past domains via meta-learning. The proposed meta-learner characterizes the similarities of the contexts of the same word in many domain corpora, which helps retrieve relevant data from the past domains to expand the new domain corpus. Experimental results show that domain embeddings produced from such a process improve the performance of the downstream tasks.

##### Abstract (translated by Google)
学习高质量的域词嵌入对于在许多NLP任务中实现良好的性能非常重要。在大规模语料库上训练的通用嵌入通常对于领域特定的应用而言是次优的。但是，特定于领域的任务通常不具有用于训练高质量域嵌入的大型域内语料库。在本文中，我们提出了一种用于域嵌入的新颖的终身学习设置。也就是说，当执行新的域嵌入时，系统已经看到了许多过去的域，并且它试图通过利用元学习从过去的域中利用语料库来扩展新的域内语料库。所提出的元学习者表征了许多领域语料库中同一词的语境的相似性，这有助于从过去的领域中检索相关数据以扩展新的领域语料库。实验结果表明，从这样的过程产生的域嵌入提高了下游任务的性能。

##### URL
[http://arxiv.org/abs/1805.09991](http://arxiv.org/abs/1805.09991)

##### PDF
[http://arxiv.org/pdf/1805.09991](http://arxiv.org/pdf/1805.09991)

