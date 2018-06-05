---
layout: post
title: "An unsupervised and customizable misspelling generator for mining noisy health-related text sources"
date: 2018-06-04 01:07:37
categories: arXiv_CL
tags: arXiv_CL
author: Abeed Sarker, Graciela Gonzalez-Hernandez
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a customizable datacentric system that automatically generates common misspellings for complex health-related terms. The spelling variant generator relies on a dense vector model learned from large unlabeled text, which is used to find semantically close terms to the original/seed keyword, followed by the filtering of terms that are lexically dissimilar beyond a given threshold. The process is executed recursively, converging when no new terms similar (lexically and semantically) to the seed keyword are found. Weighting of intra-word character sequence similarities allows further problem-specific customization of the system. On a dataset prepared for this study, our system outperforms the current state-of-the-art for medication name variant generation with best F1-score of 0.69 and F1/4-score of 0.78. Extrinsic evaluation of the system on a set of cancer-related terms showed an increase of over 67% in retrieval rate from Twitter posts when the generated variants are included. Our proposed spelling variant generator has several advantages over the current state-of-the-art and other types of variant generators-(i) it is capable of filtering out lexically similar but semantically dissimilar terms, (ii) the number of variants generated is low as many low-frequency and ambiguous misspellings are filtered out, and (iii) the system is fully automatic, customizable and easily executable. While the base system is fully unsupervised, we show how supervision maybe employed to adjust weights for task-specific customization. The performance and significant relative simplicity of our proposed approach makes it a much needed misspelling generation resource for health-related text mining from noisy sources. The source code for the system has been made publicly available for research purposes.

##### Abstract (translated by Google)
在本白皮书中，我们提供了一个可自定义的数据中心系统，可自动为复杂的健康相关术语生成常见拼写错误。拼写变量生成器依赖于从大型未标记文本中学习的密集向量模型，该模型用于查找与原始/种子关键字在语义上接近的术语，然后是对超出给定阈值的词汇不相似的术语进行过滤。当没有找到与种子关键字类似的词汇和语义的新术语时，该过程以递归方式执行，收敛。字内字符序列相似性的加权允许进一步针对特定问题定制系统。在为这项研究准备的数据集上，我们的系统胜过了目前最先进的用于药物名称变异的最新F1分数为0.69和F1 / 4分数为0.78。在一系列癌症相关术语中对系统进行的外部评估显示，当包含生成的变体时，来自Twitter帖子的检索率增加了超过67％。我们提出的拼写变体生成器比当前最先进的和其他类型的变体生成器具有几个优点 - （i）它能够过滤出词汇相似但语义上不相同的词语，（ii）生成的变体的数量是尽可能减少低频和模糊拼写错误，并且（iii）系统是全自动的，可定制的并且易于执行。虽然基础系统完全无人监督，但我们还是展示如何使用监督来调整权重以进行特定于任务的定制。我们提出的方法的性能和显着的相对简单性使其成为嘈杂信息源中用于健康相关文本挖掘的非常需要的拼写错误生成资源。该系统的源代码已公开发布用于研究目的。

##### URL
[http://arxiv.org/abs/1806.00910](http://arxiv.org/abs/1806.00910)

##### PDF
[http://arxiv.org/pdf/1806.00910](http://arxiv.org/pdf/1806.00910)

