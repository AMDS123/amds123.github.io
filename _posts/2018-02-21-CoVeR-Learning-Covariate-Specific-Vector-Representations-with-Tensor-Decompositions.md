---
layout: post
title: "CoVeR: Learning Covariate-Specific Vector Representations with Tensor Decompositions"
date: 2018-02-21 22:52:35
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Kevin Tian, Teng Zhang, James Zou
mathjax: true
---

* content
{:toc}

##### Abstract
Word embedding is a useful approach to capture co-occurrence structures in a large corpus of text. In addition to the text data itself, we often have additional covariates associated with individual documents in the corpus---e.g. the demographic of the author, time and venue of publication, etc.---and we would like the embedding to naturally capture the information of the covariates. In this paper, we propose CoVeR, a new tensor decomposition model for vector embeddings with covariates. CoVeR jointly learns a base embedding for all the words as well as a weighted diagonal transformation to model how each covariate modifies the base embedding. To obtain the specific embedding for a particular author or venue, for example, we can then simply multiply the base embedding by the transformation matrix associated with that time or venue. The main advantages of our approach is data efficiency and interpretability of the covariate transformation matrix. Our experiments demonstrate that our joint model learns substantially better embeddings conditioned on each covariate compared to the standard approach of learning a separate embedding for each covariate using only the relevant subset of data, as well as other related methods. Furthermore, CoVeR encourages the embeddings to be "topic-aligned" in the sense that the dimensions have specific independent meanings. This allows our covariate-specific embeddings to be compared by topic, enabling downstream differential analysis. We empirically evaluate the benefits of our algorithm on several datasets, and demonstrate how it can be used to address many natural questions about the effects of covariates.

##### Abstract (translated by Google)
词嵌入是一种有用的方法来捕获大量文本文集中的共现结构。除了文本数据本身之外，我们还经常在语料库中具有与单个文档相关的附加协变量，例如，作者人口统计，出版时间和地点等 - 我们希望嵌入自然地捕获协变量的信息。在本文中，我们提出CoVeR，一种新的带有协变量向量嵌入的张量分解模型。 CoVeR共同学习所有单词的基础嵌入以及加权对角变换以模拟每个协变量如何修改基础嵌入。例如，为了获得特定作者或场所的特定嵌入，我们可以简单地将基础嵌入乘以与该时间或场所相关联的变换矩阵。我们的方法的主要优点是协变量矩阵的数据效率和可解释性。我们的实验证明，与仅使用相关数据子集以及其他相关方法为每个协变量学习单独嵌入的标准方法相比，我们的联合模型学习了基于每个协变量的更好的嵌入。此外，CoVeR鼓励嵌入是“主题对齐”的，因为维度具有特定的独立含义。这使我们可以通过主题比较我们特定于协变量的嵌入，从而实现下游差异分析。我们凭经验评估了我们的算法在多个数据集上的优势，并演示了如何使用它来解决关于协变量影响的许多自然问题。

##### URL
[http://arxiv.org/abs/1802.07839](http://arxiv.org/abs/1802.07839)

##### PDF
[http://arxiv.org/pdf/1802.07839](http://arxiv.org/pdf/1802.07839)

