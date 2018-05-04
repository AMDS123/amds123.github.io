---
layout: post
title: "Joint Bootstrapping Machines for High Confidence Relation Extraction"
date: 2018-05-01 09:39:19
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Relation
author: Pankaj Gupta, Benjamin Roth, Hinrich Schütze
mathjax: true
---

* content
{:toc}

##### Abstract
Semi-supervised bootstrapping techniques for relationship extraction from text iteratively expand a set of initial seed instances. Due to the lack of labeled data, a key challenge in bootstrapping is semantic drift: if a false positive instance is added during an iteration, then all following iterations are contaminated. We introduce BREX, a new bootstrapping method that protects against such contamination by highly effective confidence assessment. This is achieved by using entity and template seeds jointly (as opposed to just one as in previous work), by expanding entities and templates in parallel and in a mutually constraining fashion in each iteration and by introducing higherquality similarity measures for templates. Experimental results show that BREX achieves an F1 that is 0.13 (0.87 vs. 0.74) better than the state of the art for four relationships.

##### Abstract (translated by Google)
用于从文本中提取关系的半监督引导技术迭代地扩展一组初始种子实例。由于缺乏标签数据，引导过程中的一个关键挑战是语义漂移：如果在迭代过程中添加了误报实例，则后面的所有迭代都会受到污染。我们引入BREX，一种新的自举方法，通过高度有效的置信度评估来防止此类污染。这是通过联合使用实体和模板种子（与之前的工作相反），通过在每次迭代中并行扩展实体和模板并以相互制约的方式并通过为模板引入更高质量的相似性度量来实现。实验结果表明，BREX比现有技术的四种关系更好地达到了0.13（0.87对0.74）的F1。

##### URL
[https://arxiv.org/abs/1805.00254](https://arxiv.org/abs/1805.00254)

##### PDF
[https://arxiv.org/pdf/1805.00254](https://arxiv.org/pdf/1805.00254)

