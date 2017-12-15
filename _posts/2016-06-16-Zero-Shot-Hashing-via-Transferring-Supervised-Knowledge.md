---
layout: post
title: "Zero-Shot Hashing via Transferring Supervised Knowledge"
date: 2016-06-16 02:56:39
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge Embedding Relation
author: Yang Yang, Weilun Chen, Yadan Luo, Fumin Shen, Jie Shao, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing has shown its efficiency and effectiveness in facilitating large-scale multimedia applications. Supervised knowledge e.g. semantic labels or pair-wise relationship) associated to data is capable of significantly improving the quality of hash codes and hash functions. However, confronted with the rapid growth of newly-emerging concepts and multimedia data on the Web, existing supervised hashing approaches may easily suffer from the scarcity and validity of supervised information due to the expensive cost of manual labelling. In this paper, we propose a novel hashing scheme, termed \emph{zero-shot hashing} (ZSH), which compresses images of "unseen" categories to binary codes with hash functions learned from limited training data of "seen" categories. Specifically, we project independent data labels i.e. 0/1-form label vectors) into semantic embedding space, where semantic relationships among all the labels can be precisely characterized and thus seen supervised knowledge can be transferred to unseen classes. Moreover, in order to cope with the semantic shift problem, we rotate the embedded space to more suitably align the embedded semantics with the low-level visual feature space, thereby alleviating the influence of semantic gap. In the meantime, to exert positive effects on learning high-quality hash functions, we further propose to preserve local structural property and discrete nature in binary codes. Besides, we develop an efficient alternating algorithm to solve the ZSH model. Extensive experiments conducted on various real-life datasets show the superior zero-shot image retrieval performance of ZSH as compared to several state-of-the-art hashing methods.

##### Abstract (translated by Google)
散列已经显示出它在促进大规模多媒体应用方面的效率和有效性。监督知识语义标签或成对关系）能够显着提高散列码和散列函数的质量。然而，面对网络上新兴概念和多媒体数据的快速增长，现有的监督哈希方法由于手工标注的成本昂贵，很容易受到监督信息的稀缺性和有效性的影响。在本文中，我们提出了一种新颖的哈希方案，称为\ emph {zero-shot hashing}（ZSH），它将“看不见”的类别的图像压缩成二进制编码。具体而言，我们将独立的数据标签（即0/1形式的标签向量）投影到语义嵌入空间中，其中可以精确地表征所有标签之间的语义关系，从而可以将看到的监督知识转移到看不见的类别。而且，为了应对语义转换问题，我们旋转嵌入的空间以更适合地将嵌入语义与低级视觉特征空间对齐，从而减轻语义差距的影响。同时，为了发挥学习高质量哈希函数的积极作用，我们进一步提出保留二进制编码的局部结构性质和离散性质。此外，我们开发了一个有效的交替算法来解决ZSH模型。在各种实际数据集上进行的大量实验表明，与几种最先进的哈希方法相比，ZSH具有出色的零镜头图像检索性能。

##### URL
[https://arxiv.org/abs/1606.05032](https://arxiv.org/abs/1606.05032)

##### PDF
[https://arxiv.org/pdf/1606.05032](https://arxiv.org/pdf/1606.05032)

