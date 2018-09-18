---
layout: post
title: "Probabilistic DL Reasoning with Pinpointing Formulas: A Prolog-based Approach"
date: 2018-09-17 13:13:02
categories: arXiv_AI
tags: arXiv_AI Inference
author: Riccardo Zese, Elena Bellodi, Giuseppe Cota, Evelina Lamma, Fabrizio Riguzzi
mathjax: true
---

* content
{:toc}

##### Abstract
When modeling real world domains we have to deal with information that is incomplete or that comes from sources with different trust levels. This motivates the need for managing uncertainty in the Semantic Web. To this purpose, we introduced a probabilistic semantics, named DISPONTE, in order to combine description logics with probability theory. The probability of a query can be then computed from the set of its explanations by building a Binary Decision Diagram (BDD). The set of explanations can be found using the tableau algorithm, which has to handle non-determinism. Prolog, with its efficient handling of non-determinism, is suitable for implementing the tableau algorithm. TRILL and TRILLP are systems offering a Prolog implementation of the tableau algorithm. TRILLP builds a pinpointing formula, that compactly represents the set of explanations and can be directly translated into a BDD. Both reasoners were shown to outperform state-of-the-art DL reasoners. In this paper, we present an improvement of TRILLP, named TORNADO, in which the BDD is directly built during the construction of the tableau, further speeding up the overall inference process. An experimental comparison shows the effectiveness of TORNADO. All systems can be tried online in the TRILL on SWISH web application at <a href="http://trill.ml.unife.it/.">this http URL</a>

##### Abstract (translated by Google)
在对现实世界域进行建模时，我们必须处理不完整的信息或来自具有不同信任级别的信息的信息。这激发了管理语义Web中不确定性的需求。为此，我们引入了一个名为DISPONTE的概率语义，以便将描述逻辑与概率理论相结合。然后可以通过构建二进制决策图（BDD）从其解释集合计算查询的概率。可以使用tableau算法找到解释集，该算法必须处理非确定性。 Prolog具有高效的非确定性处理，适用于实现tableau算法。 TRILL和TRILLP是提供tableau算法的Prolog实现的系统。 TRILLP构建精确定位公式，紧凑地表示一组解释并可直接转换为BDD。两位参赛者都表现出优于最先进的DL推荐者。在本文中，我们提出了TRILLP的改进，名为TORNADO，其中BDD在构建画面期间直接构建，进一步加快了整体推理过程。实验对比显示了TORNADO的有效性。所有系统都可以在SWISH网络应用程序的TRILL上在线试用，网址为<a href="http://trill.ml.unife.it/.">此http URL </a>

##### URL
[http://arxiv.org/abs/1809.06180](http://arxiv.org/abs/1809.06180)

##### PDF
[http://arxiv.org/pdf/1809.06180](http://arxiv.org/pdf/1809.06180)

