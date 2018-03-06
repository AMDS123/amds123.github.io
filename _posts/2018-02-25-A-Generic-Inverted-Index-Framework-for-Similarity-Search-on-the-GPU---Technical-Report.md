---
layout: post
title: "A Generic Inverted Index Framework for Similarity Search on the GPU - Technical Report"
date: 2018-02-25 06:05:25
categories: arXiv_CV
tags: arXiv_CV
author: Jingbo Zhou, Qi Guo, H. V. Jagadish, Lubo&#x161; Kr&#x10d;&#xe1;l, Siyuan Liu, Wenhao Luan, Anthony K. H. Tung, Yueji Yang, Yuxin Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel generic inverted index framework on the GPU (called GENIE), aiming to reduce the programming complexity of the GPU for parallel similarity search of different data types. Not every data type and similarity measure are supported by GENIE, but many popular ones are. We present the system design of GENIE, and demonstrate similarity search with GENIE on several data types along with a theoretical analysis of search results. A new concept of locality sensitive hashing (LSH) named $\tau$-ANN search, and a novel data structure c-PQ on the GPU are also proposed for achieving this purpose. Extensive experiments on different real-life datasets demonstrate the efficiency and effectiveness of our framework. The implemented system has been released as open source.

##### Abstract (translated by Google)
我们在GPU上提出了一种新的通用倒排索引框架（称为GENIE），旨在降低用于不同数据类型的并行相似搜索的GPU的编程复杂度。 GENIE不支持每种数据类型和相似度度量，但许多流行的度量值都是。我们介绍了GENIE的系统设计，并展示了GENIE在几种数据类型上的相似搜索以及对搜索结果的理论分析。还提出了一种名为$ \ tau $ -ANN搜索的局部敏感散列（LSH）的新概念，并且还提出了GPU上的新型数据结构c-PQ来实现此目的。针对不同实际数据集的广泛实验证明了我们框架的效率和有效性。实施的系统已经作为开源发布。

##### URL
[http://arxiv.org/abs/1603.08390](http://arxiv.org/abs/1603.08390)

##### PDF
[http://arxiv.org/pdf/1603.08390](http://arxiv.org/pdf/1603.08390)

