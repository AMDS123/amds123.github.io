---
layout: post
title: "AMR Parsing as Graph Prediction with Latent Alignment"
date: 2018-05-14 16:56:36
categories: arXiv_CL
tags: arXiv_CL Inference Prediction Relation
author: Chunchuan Lyu, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
Abstract meaning representations (AMRs) are broad-coverage sentence-level semantic representations. AMRs represent sentences as rooted labeled directed acyclic graphs. AMR parsing is challenging partly due to the lack of annotated alignments between nodes in the graphs and words in the corresponding sentences. We introduce a neural parser which treats alignments as latent variables within a joint probabilistic model of concepts, relations and alignments. As exact inference requires marginalizing over alignments and is infeasible, we use the variational auto-encoding framework and a continuous relaxation of the discrete alignments. We show that joint modeling is preferable to using a pipeline of align and parse. The parser achieves the best reported results on the standard benchmark (74.4% on LDC2016E25).

##### Abstract (translated by Google)
抽象意义表征（AMRs）是广义的句子级语义表征。 AMR将句子表示为有根标签的有向无环图。 AMR解析是有挑战性的，部分原因是缺乏图中节点与相应句子中的单词之间的注释对齐。我们引入了一个神经解析器，它将对齐作为概念，关系和对齐的联合概率模型中的潜在变量。由于精确推理需要边界对齐而不可行，我们使用变分自动编码框架和连续放松离散对齐。我们表明，联合建模优于使用对齐和分析的管道。解析器在标准基准测试中达到最佳报告结果（LDC2016E25的测试结果为74.4％）。

##### URL
[https://arxiv.org/abs/1805.05286](https://arxiv.org/abs/1805.05286)

##### PDF
[https://arxiv.org/pdf/1805.05286](https://arxiv.org/pdf/1805.05286)

