---
layout: post
title: "Predicting Disease-Gene Associations using Cross-Document Graph-based Features"
date: 2017-09-26 19:59:16
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Hendrik ter Horst, Matthias Hartung, Roman Klinger, Matthias Zwick, Philipp Cimiano
mathjax: true
---

* content
{:toc}

##### Abstract
In the context of personalized medicine, text mining methods pose an interesting option for identifying disease-gene associations, as they can be used to generate novel links between diseases and genes which may complement knowledge from structured databases. The most straightforward approach to extract such links from text is to rely on a simple assumption postulating an association between all genes and diseases that co-occur within the same document. However, this approach (i) tends to yield a number of spurious associations, (ii) does not capture different relevant types of associations, and (iii) is incapable of aggregating knowledge that is spread across documents. Thus, we propose an approach in which disease-gene co-occurrences and gene-gene interactions are represented in an RDF graph. A machine learning-based classifier is trained that incorporates features extracted from the graph to separate disease-gene pairs into valid disease-gene associations and spurious ones. On the manually curated Genetic Testing Registry, our approach yields a 30 points increase in F1 score over a plain co-occurrence baseline.

##### Abstract (translated by Google)
在个体化医学的背景下，文本挖掘方法为识别疾病 - 基因关联提供了一个有趣的选择，因为它们可以用来在疾病和基因之间产生新的联系，从而可以补充来自结构化数据库的知识。从文本中提取这种链接最直接的方法是依靠一个简单的假设，假设所有基因和疾病在同一文件中共同发生的关联。然而，这种方法（i）倾向于产生许多虚假的关联，（ii）没有捕捉到不同的相关类型的关联，以及（iii）不能汇集分散在文档中的知识。因此，我们提出一种在RDF图中表示疾病 - 基因共同发生和基因 - 基因相互作用的方法。基于机器学习的分类器被训练，该分类器结合从图中提取的特征以将疾病 - 基因对分离成有效的疾病 - 基因关联和虚假的关联。在手工策划的基因测试注册表中，我们的方法在平均同现基线上得到30分的F1分数。

##### URL
[https://arxiv.org/abs/1709.09239](https://arxiv.org/abs/1709.09239)

##### PDF
[https://arxiv.org/pdf/1709.09239](https://arxiv.org/pdf/1709.09239)

