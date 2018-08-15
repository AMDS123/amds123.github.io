---
layout: post
title: "A Generic Inverted Index Framework for Similarity Search on the GPU - Technical Report"
date: 2018-08-14 08:49:16
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
我们在GPU（称为GENIE）上提出了一种新颖的通用倒排索引框架，旨在降低GPU的编程复杂度，以便对不同数据类型进行并行相似性搜索。 GENIE并不支持每种数据类型和相似性度量，但许多流行的都是。我们介绍了GENIE的系统设计，并展示了与GENIE在几种数据类型上的相似性搜索以及对搜索结果的理论分析。为了实现这一目的，还提出了一种名为$ \ tau $ -ANN搜索的局部敏感散列（LSH）的新概念，以及GPU上的新颖数据结构c-PQ。对不同真实数据集的广泛实验证明了我们框架的效率和有效性。已实施的系统已作为开源发布。

##### URL
[http://arxiv.org/abs/1603.08390](http://arxiv.org/abs/1603.08390)

##### PDF
[http://arxiv.org/pdf/1603.08390](http://arxiv.org/pdf/1603.08390)

