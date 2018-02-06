---
layout: post
title: "Pair-Linking for Collective Entity Disambiguation: Two Could Be Better Than All"
date: 2018-02-04 05:50:39
categories: arXiv_CL
tags: arXiv_CL Knowledge Optimization Relation
author: Minh C. Phan, Aixin Sun, Yi Tay, Jialong Han, Chenliang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Collective entity disambiguation, or collective entity linking aims to jointly resolve multiple mentions by linking them to their associated entities in a knowledge base. Previous works largely based on the underlying assumption that entities within the same document are highly related. However, the extend to which these mentioned entities are actually connected in reality is rarely studied and therefore raises interesting research questions. For the first time, this paper shows that the semantic relationships between mentioned entities within documents are in fact less dense than expected. This could be attributed to several reasons such as noise, data sparsity and knowledge base incompleteness. As a remedy, we introduces MINTREE, a new tree-based objective for the problem of entity disambiguation. The key intuition behind MINTREE is the concept of coherence relaxation which utilizes the weight of a minimum spanning tree to measure the coherence between entities. Based on this new objective, we devise a novel iterative solution for MINTREE optimization problem which we call Pair-Linking. The idea of Pair-Linking is simple: instead of considering all the given mentions, Pair-Linking iteratively selects the pair with highest confidence at each step for decision making. Via extensive experiments on 8 publicly available benchmark datasets, we show that our approach is not only more accurate but also surprisingly faster than many state-of-the-art collective linking algorithms.

##### Abstract (translated by Google)
集体实体消歧或集体实体关联旨在联合解决多个提及，将它们与知识库中的相关实体联系起来。之前的工作主要基于假设同一文件中的实体高度相关。但是，实际上这些实体实际上连接的范围很少被研究，因此引起了有趣的研究问题。本文首次表明文档中提到的实体之间的语义关系事实上比预期的要小。这可能是由于噪声，数据稀疏性和知识库不完整性等原因造成的。作为一种补救措施，我们引入了MINTREE，这是一个针对实体消歧问题的基于树的新目标。 MINTREE背后的关键直觉是相干松弛的概念，它利用最小生成树的权重来衡量实体之间的一致性。基于这个新的目标，我们为MINTREE优化问题设计了一种新的迭代解决方案，我们称之为Pair-Linking。对联的思想是简单的：而不是考虑所有给定的提及，Pair-Linking迭代地选择在每个步骤具有最高置信度的对来做出决定。通过对8个公开可用的基准数据集进行广泛的实验，我们发现，我们的方法不仅比现有技术中最先进的集体链接算法更准确，而且还令人惊讶地更快。

##### URL
[http://arxiv.org/abs/1802.01074](http://arxiv.org/abs/1802.01074)

##### PDF
[http://arxiv.org/pdf/1802.01074](http://arxiv.org/pdf/1802.01074)

