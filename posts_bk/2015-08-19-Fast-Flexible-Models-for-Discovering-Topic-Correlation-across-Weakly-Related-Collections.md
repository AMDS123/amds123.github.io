---
layout: post
title: "Fast, Flexible Models for Discovering Topic Correlation across Weakly-Related Collections"
date: 2015-08-19 08:30:37
categories: arXiv_CL
tags: arXiv_CL Relation
author: Jingwei Zhang, Aaron Gerow, Jaan Altosaar, James Evans, Richard Jean So
mathjax: true
---

* content
{:toc}

##### Abstract
Weak topic correlation across document collections with different numbers of topics in individual collections presents challenges for existing cross-collection topic models. This paper introduces two probabilistic topic models, Correlated LDA (C-LDA) and Correlated HDP (C-HDP). These address problems that can arise when analyzing large, asymmetric, and potentially weakly-related collections. Topic correlations in weakly-related collections typically lie in the tail of the topic distribution, where they would be overlooked by models unable to fit large numbers of topics. To efficiently model this long tail for large-scale analysis, our models implement a parallel sampling algorithm based on the Metropolis-Hastings and alias methods (Yuan et al., 2015). The models are first evaluated on synthetic data, generated to simulate various collection-level asymmetries. We then present a case study of modeling over 300k documents in collections of sciences and humanities research from JSTOR.

##### Abstract (translated by Google)
单个集合中具有不同主题数量的文档集合之间的弱主题相关性对现有的跨集合主题模型提出了挑战。本文介绍了两个概率主题模型，相关LDA（C-LDA）和相关HDP（C-HDP）。这些解决了分析大型，不对称和可能较弱相关集合时可能出现的问题。弱相关集合中的主题相关性通常位于主题分布的尾部，在这些主题分布中，模型不能适应大量的主题。为了有效地对这个长尾进行大规模分析，我们的模型实现了基于Metropolis-Hastings和别名方法的并行采样算法（Yuan et al。，2015）。首先对合成数据进行模型评估，模拟各种集合级别的不对称。然后，我们提供了一个案例研究，对JSTOR的科学和人文科学研究集合中的30万多个文档进行建模。

##### URL
[https://arxiv.org/abs/1508.04562](https://arxiv.org/abs/1508.04562)

##### PDF
[https://arxiv.org/pdf/1508.04562](https://arxiv.org/pdf/1508.04562)

