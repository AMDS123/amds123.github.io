---
layout: post
title: "BattRAE: Bidimensional Attention-Based Recursive Autoencoders for Learning Bilingual Phrase Embeddings"
date: 2016-11-25 03:26:45
categories: arXiv_CL
tags: arXiv_CL Attention Embedding
author: Biao Zhang, Deyi Xiong, Jinsong Su
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a bidimensional attention based recursive autoencoder (BattRAE) to integrate clues and sourcetarget interactions at multiple levels of granularity into bilingual phrase representations. We employ recursive autoencoders to generate tree structures of phrases with embeddings at different levels of granularity (e.g., words, sub-phrases and phrases). Over these embeddings on the source and target side, we introduce a bidimensional attention network to learn their interactions encoded in a bidimensional attention matrix, from which we extract two soft attention weight distributions simultaneously. These weight distributions enable BattRAE to generate compositive phrase representations via convolution. Based on the learned phrase representations, we further use a bilinear neural model, trained via a max-margin method, to measure bilingual semantic similarity. To evaluate the effectiveness of BattRAE, we incorporate this semantic similarity as an additional feature into a state-of-the-art SMT system. Extensive experiments on NIST Chinese-English test sets show that our model achieves a substantial improvement of up to 1.63 BLEU points on average over the baseline.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于二维注意的递归自动编码器（BattRAE），将多个粒度级的线索和源目标相互作用整合到双语短语表示中。我们使用递归自动编码器来生成具有不同粒度级别（例如，单词，子短语和短语）的嵌入的短语的树结构。在源和目标侧的这些嵌入中，我们引入一个二维注意网络来学习他们在二维注意矩阵中编码的相互作用，从而同时提取两个软注意力分布。这些权重分布使BattRAE能够通过卷积生成合成的短语表示。基于学习的短语表示，我们进一步使用双线性神经模型，通过最大余量方法训练来测量双语语义相似度。为了评估BattRAE的有效性，我们将这种语义相似性作为附加特性纳入了最先进的SMT系统。对NIST中英文测试集进行的大量实验表明，我们的模型在基线上平均可以达到1.63 BLEU点的实质性改进。

##### URL
[https://arxiv.org/abs/1605.07874](https://arxiv.org/abs/1605.07874)

##### PDF
[https://arxiv.org/pdf/1605.07874](https://arxiv.org/pdf/1605.07874)

