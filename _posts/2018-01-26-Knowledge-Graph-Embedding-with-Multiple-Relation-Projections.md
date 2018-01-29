---
layout: post
title: "Knowledge Graph Embedding with Multiple Relation Projections"
date: 2018-01-26 00:28:51
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Sparse Knowledge Embedding Prediction Relation
author: Kien Do, Truyen Tran, Svetha Venkatesh
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge graphs contain rich relational structures of the world, and thus complement data-driven machine learning in heterogeneous data. One of the most effective methods in representing knowledge graphs is to embed symbolic relations and entities into continuous spaces, where relations are approximately linear translation between projected images of entities in the relation space. However, state-of-the-art relation projection methods such as TransR, TransD or TransSparse do not model the correlation between relations, and thus are not scalable to complex knowledge graphs with thousands of relations, both in computational demand and in statistical robustness. To this end we introduce TransF, a novel translation-based method which mitigates the burden of relation projection by explicitly modeling the basis subspaces of projection matrices. As a result, TransF is far more light weight than the existing projection methods, and is robust when facing a high number of relations. Experimental results on the canonical link prediction task show that our proposed model outperforms competing rivals by a large margin and achieves state-of-the-art performance. Especially, TransF improves by 9%/5% in the head/tail entity prediction task for N-to-1/1-to-N relations over the best performing translation-based method.

##### Abstract (translated by Google)
知识图包含丰富的世界关系结构，从而补充异构数据中的数据驱动的机器学习。表示知识图的最有效的方法之一是将符号关系和实体嵌入到连续的空间中，其中关系是关系空间中实体的投影图像之间的近似线性转换。然而，诸如TransR，TransD或TransSparse之类的最先进的关系投影方法不能模拟关系之间的相关性，因此不能在具有数千个关系的复杂知识图中进行扩展，无论是在计算需求和统计稳健性方面。为此，我们引入TransF，这是一种新颖的基于翻译的方法，通过显式建模投影矩阵的基本子空间来减轻关系投影的负担。结果，TransF比现有的投影方法轻得多，并且在面对大量关系时是稳健的。典型链接预测任务的实验结果表明，我们提出的模型胜过竞争对手大幅度的实现了最先进的性能。特别是在最好的基于翻译的方法中，对于N对1/1对N关系，在头/尾实体预测任务中，TransF提高了9％/ 5％。

##### URL
[http://arxiv.org/abs/1801.08641](http://arxiv.org/abs/1801.08641)

##### PDF
[http://arxiv.org/pdf/1801.08641](http://arxiv.org/pdf/1801.08641)

