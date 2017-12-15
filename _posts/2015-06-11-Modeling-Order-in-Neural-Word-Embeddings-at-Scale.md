---
layout: post
title: "Modeling Order in Neural Word Embeddings at Scale"
date: 2015-06-11 03:00:29
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model Relation
author: Andrew Trask, David Gilmore, Matthew Russell
mathjax: true
---

* content
{:toc}

##### Abstract
Natural Language Processing (NLP) systems commonly leverage bag-of-words co-occurrence techniques to capture semantic and syntactic word relationships. The resulting word-level distributed representations often ignore morphological information, though character-level embeddings have proven valuable to NLP tasks. We propose a new neural language model incorporating both word order and character order in its embedding. The model produces several vector spaces with meaningful substructure, as evidenced by its performance of 85.8% on a recent word-analogy task, exceeding best published syntactic word-analogy scores by a 58% error margin. Furthermore, the model includes several parallel training methods, most notably allowing a skip-gram network with 160 billion parameters to be trained overnight on 3 multi-core CPUs, 14x larger than the previous largest neural network.

##### Abstract (translated by Google)
自然语言处理（NLP）系统通常利用词袋共现技术来捕获语义和句法单词关系。由此产生的字级分布式表示经常忽略形态信息，虽然字符级嵌入已被证明是有价值的NLP任务。我们提出了一种新的神经语言模型，在其嵌入中结合了词序和字符顺序。该模型产生了具有有意义的子结构的多个向量空间，如通过最近的词类比任务的85.8％的表现所证明的，超过最佳公开的句法词类比分数58％的误差。此外，该模型还包括几种平行的训练方法，最明显的是允许一个拥有1600亿参数的skip-gram网络在3个多核CPU上通宵训练，比以前最大的神经网络大14倍。

##### URL
[https://arxiv.org/abs/1506.02338](https://arxiv.org/abs/1506.02338)

##### PDF
[https://arxiv.org/pdf/1506.02338](https://arxiv.org/pdf/1506.02338)

