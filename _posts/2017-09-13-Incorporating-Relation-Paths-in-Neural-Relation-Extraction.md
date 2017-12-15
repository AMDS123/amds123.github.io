---
layout: post
title: "Incorporating Relation Paths in Neural Relation Extraction"
date: 2017-09-13 19:30:06
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Inference Relation
author: Wenyuan Zeng, Yankai Lin, Zhiyuan Liu, Maosong Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Distantly supervised relation extraction has been widely used to find novel relational facts from plain text. To predict the relation between a pair of two target entities, existing methods solely rely on those direct sentences containing both entities. In fact, there are also many sentences containing only one of the target entities, which provide rich and useful information for relation extraction. To address this issue, we build inference chains between two target entities via intermediate entities, and propose a path-based neural relation extraction model to encode the relational semantics from both direct sentences and inference chains. Experimental results on real-world datasets show that, our model can make full use of those sentences containing only one target entity, and achieves significant and consistent improvements on relation extraction as compared with baselines. The source code of this paper can be obtained from https: //github.com/thunlp/PathNRE.

##### Abstract (translated by Google)
远程监督关系抽取已被广泛用于从纯文本中找到新的关系事实。为了预测一对两个目标实体之间的关系，现有的方法完全依赖于包含两个实体的直接句子。实际上，也有很多句子只包含一个目标实体，为关系提取提供丰富有用的信息。为解决这个问题，我们通过中间实体建立两个目标实体之间的推理链，并提出了一个基于路径的神经关系提取模型来对直接句子和推理链中的关系语义进行编码。对实际数据集的实验结果表明，我们的模型可以充分利用那些只包含一个目标实体的语句，并且与基线相比，对关系抽取实现了显着而一致的改进。本文的源代码可以从https：//github.com/thunlp/PathNRE获得。

##### URL
[https://arxiv.org/abs/1609.07479](https://arxiv.org/abs/1609.07479)

##### PDF
[https://arxiv.org/pdf/1609.07479](https://arxiv.org/pdf/1609.07479)

