---
layout: post
title: "Topic supervised non-negative matrix factorization"
date: 2017-07-02 16:00:27
categories: arXiv_CL
tags: arXiv_CL GAN Optimization
author: Kelsey MacMillan, James D. Wilson
mathjax: true
---

* content
{:toc}

##### Abstract
Topic models have been extensively used to organize and interpret the contents of large, unstructured corpora of text documents. Although topic models often perform well on traditional training vs. test set evaluations, it is often the case that the results of a topic model do not align with human interpretation. This interpretability fallacy is largely due to the unsupervised nature of topic models, which prohibits any user guidance on the results of a model. In this paper, we introduce a semi-supervised method called topic supervised non-negative matrix factorization (TS-NMF) that enables the user to provide labeled example documents to promote the discovery of more meaningful semantic structure of a corpus. In this way, the results of TS-NMF better match the intuition and desired labeling of the user. The core of TS-NMF relies on solving a non-convex optimization problem for which we derive an iterative algorithm that is shown to be monotonic and convergent to a local optimum. We demonstrate the practical utility of TS-NMF on the Reuters and PubMed corpora, and find that TS-NMF is especially useful for conceptual or broad topics, where topic key terms are not well understood. Although identifying an optimal latent structure for the data is not a primary objective of the proposed approach, we find that TS-NMF achieves higher weighted Jaccard similarity scores than the contemporary methods, (unsupervised) NMF and latent Dirichlet allocation, at supervision rates as low as 10% to 20%.

##### Abstract (translated by Google)
主题模型已被广泛用于组织和解释文本文档的大型非结构化语料库的内容。虽然主题模型在传统培训和测试集评估方面通常表现良好，但主题模型的结果往往与人类解释不一致。这种可解释性的谬误很大程度上是由于主题模型的无监督性质，它禁止任何用户对模型结果的指导。在本文中，我们引入了一个称为主题监督非负矩阵分解（TS-NMF）的半监督方法，使用户能够提供带标签的示例文档来促进发现更有意义的语料库语义结构。这样，TS-NMF的结果更好地匹配用户的直觉和所需的标签。 TS-NMF的核心依赖于求解一个非凸优化问题，从而得到一个迭代算法，该算法被证明是单调收敛于局部最优的。我们展示TS-NMF在路透社和PubMed语料库上的实际效用，发现TS-NMF对概念性或广义话题特别有用，因为话题关键术语不是很好理解。尽管确定数据的最佳潜在结构不是所提出的方法的主要目标，但是我们发现TS-NMF的加权Jaccard相似度得分高于当代方法（无监督）NMF和潜在Dirichlet分配，监督率低为10％至20％。

##### URL
[https://arxiv.org/abs/1706.05084](https://arxiv.org/abs/1706.05084)

##### PDF
[https://arxiv.org/pdf/1706.05084](https://arxiv.org/pdf/1706.05084)

