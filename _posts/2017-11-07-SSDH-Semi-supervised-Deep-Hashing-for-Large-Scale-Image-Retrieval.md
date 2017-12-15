---
layout: post
title: "SSDH: Semi-supervised Deep Hashing for Large Scale Image Retrieval"
date: 2017-11-07 03:23:28
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge Embedding
author: Jian Zhang, Yuxin Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing methods have been widely used for efficient similarity retrieval on large scale image database. Traditional hashing methods learn hash functions to generate binary codes from hand-crafted features, which achieve limited accuracy since the hand-crafted features cannot optimally represent the image content and preserve the semantic similarity. Recently, several deep hashing methods have shown better performance because the deep architectures generate more discriminative feature representations. However, these deep hashing methods are mainly designed for supervised scenarios, which only exploit the semantic similarity information, but ignore the underlying data structures. In this paper, we propose the semi-supervised deep hashing (SSDH) approach, to perform more effective hash function learning by simultaneously preserving semantic similarity and underlying data structures. The main contributions are as follows: (1) We propose a semi-supervised loss to jointly minimize the empirical error on labeled data, as well as the embedding error on both labeled and unlabeled data, which can preserve the semantic similarity and capture the meaningful neighbors on the underlying data structures for effective hashing. (2) A semi-supervised deep hashing network is designed to extensively exploit both labeled and unlabeled data, in which we propose an online graph construction method to benefit from the evolving deep features during training to better capture semantic neighbors. To the best of our knowledge, the proposed deep network is the first deep hashing method that can perform hash code learning and feature learning simultaneously in a semi-supervised fashion. Experimental results on 5 widely-used datasets show that our proposed approach outperforms the state-of-the-art hashing methods.

##### Abstract (translated by Google)
散列方法被广泛用于大规模图像数据库的高效相似性检索。传统的哈希方法学习哈希函数来从手工特征生成二进制代码，由于手工特征不能最佳地表示图像内容并保持语义相似性，所以手动特征达到有限的准确性。最近，几种深度哈希方法已经表现出更好的性能，因为深层架构产生更多的判别性特征表示。然而，这些深度哈希方法主要是为监督场景设计的，它们只利用语义相似度信息，而忽略底层的数据结构。在本文中，我们提出了半监督深度散列（SSDH）方法，通过同时保留语义相似性和底层数据结构来执行更有效的散列函数学习。主要贡献如下：（1）提出了一种半监督损失的方法，将标记数据的经验误差和标记数据与未标记数据的嵌入误差联合最小化，从而保持语义相似性和捕获有意义的基础数据结构上的邻居进行有效散列。 （2）设计了一个半监督深度散列网络，广泛的利用标签数据和未标签数据，提出了一种在线图形构造方法，利用训练过程中的深层特征，更好地捕捉语义邻居。据我们所知，所提出的深度网络是第一个能够以半监督的方式同时进行哈希码学习和特征学习的深度哈希方法。 5个广泛使用的数据集上的实验结果表明，我们提出的方法胜过最先进的散列方法。

##### URL
[https://arxiv.org/abs/1607.08477](https://arxiv.org/abs/1607.08477)

##### PDF
[https://arxiv.org/pdf/1607.08477](https://arxiv.org/pdf/1607.08477)

