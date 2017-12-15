---
layout: post
title: "End-to-End Neural Ad-hoc Ranking with Kernel Pooling"
date: 2017-06-20 18:19:54
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Chenyan Xiong, Zhuyun Dai, Jamie Callan, Zhiyuan Liu, Russell Power
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes K-NRM, a kernel based neural model for document ranking. Given a query and a set of documents, K-NRM uses a translation matrix that models word-level similarities via word embeddings, a new kernel-pooling technique that uses kernels to extract multi-level soft match features, and a learning-to-rank layer that combines those features into the final ranking score. The whole model is trained end-to-end. The ranking layer learns desired feature patterns from the pairwise ranking loss. The kernels transfer the feature patterns into soft-match targets at each similarity level and enforce them on the translation matrix. The word embeddings are tuned accordingly so that they can produce the desired soft matches. Experiments on a commercial search engine's query log demonstrate the improvements of K-NRM over prior feature-based and neural-based states-of-the-art, and explain the source of K-NRM's advantage: Its kernel-guided embedding encodes a similarity metric tailored for matching query words to document words, and provides effective multi-level soft matches.

##### Abstract (translated by Google)
本文提出了基于核的文档排序神经模型K-NRM。给定一个查询和一组文档，K-NRM使用一个翻译矩阵来模拟字级相似性，通过字嵌入，一个新的内核池技术，使用内核提取多级软匹配功能，将这些特征组合到最终的评分中。整个模型是端到端的训练。排名层从成对排名损失中学习期望的特征模式。内核将特征模式转换为每个相似度级别的软匹配目标，并在转换矩阵上执行。嵌入这个词是相应的调整，以便他们可以产生所需的软匹配。在商业搜索引擎的查询日志上的实验证明了K-NRM相对于基于先前特征的和基于神经的最新状态的改进，并且解释了K-NRM优点的来源：其内核引导的嵌入编码相似度度量标准，将查询词与文档词进行匹配，提供有效的多级软匹配。

##### URL
[https://arxiv.org/abs/1706.06613](https://arxiv.org/abs/1706.06613)

##### PDF
[https://arxiv.org/pdf/1706.06613](https://arxiv.org/pdf/1706.06613)

