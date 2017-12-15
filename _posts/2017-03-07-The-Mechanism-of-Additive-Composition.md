---
layout: post
title: "The Mechanism of Additive Composition"
date: 2017-03-07 02:39:58
categories: arXiv_CL
tags: arXiv_CL
author: Ran Tian, Naoaki Okazaki, Kentaro Inui
mathjax: true
---

* content
{:toc}

##### Abstract
Additive composition (Foltz et al, 1998; Landauer and Dumais, 1997; Mitchell and Lapata, 2010) is a widely used method for computing meanings of phrases, which takes the average of vector representations of the constituent words. In this article, we prove an upper bound for the bias of additive composition, which is the first theoretical analysis on compositional frameworks from a machine learning point of view. The bound is written in terms of collocation strength; we prove that the more exclusively two successive words tend to occur together, the more accurate one can guarantee their additive composition as an approximation to the natural phrase vector. Our proof relies on properties of natural language data that are empirically verified, and can be theoretically derived from an assumption that the data is generated from a Hierarchical Pitman-Yor Process. The theory endorses additive composition as a reasonable operation for calculating meanings of phrases, and suggests ways to improve additive compositionality, including: transforming entries of distributional word vectors by a function that meets a specific condition, constructing a novel type of vector representations to make additive composition sensitive to word order, and utilizing singular value decomposition to train word vectors.

##### Abstract (translated by Google)
添加剂组合物（Foltz等，1998; Landauer和Dumais，1997; Mitchell和Lapata，2010）是一种广泛使用的计算短语含义的方法，它取构成词向量表示的平均值。在这篇文章中，我们证明了加法构成偏差的上界，这是从机器学习的角度对构成框架进行的第一个理论分析。这个界限是用搭配力量来写的。我们证明了两个连续的词更倾向于一起出现，更准确的可以保证它们的加法组合作为一个近似的自然短语向量。我们的证明依赖于经验证实的自然语言数据的属性，理论上可以从数据是从分层Pitman-Yor过程中产生的假设推导出来的。该理论认为加法合成是一种计算短语意义的合理操作，并提出了改善加性组合性的方法，包括：通过满足特定条件的函数转换分布式词向量的条目，构造一种新型的向量表示形式对词序敏感的词组合，利用奇异值分解训练词向量。

##### URL
[https://arxiv.org/abs/1511.08407](https://arxiv.org/abs/1511.08407)

##### PDF
[https://arxiv.org/pdf/1511.08407](https://arxiv.org/pdf/1511.08407)

