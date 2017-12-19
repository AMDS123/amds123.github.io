---
layout: post
title: "Improving Term Frequency Normalization for Multi-topical Documents, and Application to Language Modeling Approaches"
date: 2015-02-08 17:32:44
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Seung-Hoon Na, In-Su Kang, Jong-Hyeok Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Term frequency normalization is a serious issue since lengths of documents are various. Generally, documents become long due to two different reasons - verbosity and multi-topicality. First, verbosity means that the same topic is repeatedly mentioned by terms related to the topic, so that term frequency is more increased than the well-summarized one. Second, multi-topicality indicates that a document has a broad discussion of multi-topics, rather than single topic. Although these document characteristics should be differently handled, all previous methods of term frequency normalization have ignored these differences and have used a simplified length-driven approach which decreases the term frequency by only the length of a document, causing an unreasonable penalization. To attack this problem, we propose a novel TF normalization method which is a type of partially-axiomatic approach. We first formulate two formal constraints that the retrieval model should satisfy for documents having verbose and multi-topicality characteristic, respectively. Then, we modify language modeling approaches to better satisfy these two constraints, and derive novel smoothing methods. Experimental results show that the proposed method increases significantly the precision for keyword queries, and substantially improves MAP (Mean Average Precision) for verbose queries.

##### Abstract (translated by Google)
由于文档的长度各不相同，术语频率归一化是一个严重的问题。一般来说，文件由于两个不同的原因而变长 - 冗长和多重话题。首先，冗长意味着相同的话题通过与话题相关的术语被重复提及，所以术语频率比概括的更多。其次，多重话题表明文档对多个主题进行了广泛的讨论，而不是单个主题。尽管这些文档特征应该被不同地处理，但是所有以前的词频归一化方法忽略了这些差异，并且使用了简化的长度驱动的方法，其将文档的频率减少了仅仅是文档的长度，导致不合理的惩罚。为了解决这个问题，我们提出了一种新的TF归一化方法，它是一种部分 - 公理化的方法。我们首先制定两个形式约束，检索模型分别应该满足文件具有冗长和多重的话题性。然后，我们修改语言建模方法，以更好地满足这两个约束，并导出新颖的平滑方法。实验结果表明，所提出的方法显着提高了关键字查询的精度，并大大提高了详细查询的MAP（平均精度）。

##### URL
[https://arxiv.org/abs/1502.02277](https://arxiv.org/abs/1502.02277)

##### PDF
[https://arxiv.org/pdf/1502.02277](https://arxiv.org/pdf/1502.02277)

