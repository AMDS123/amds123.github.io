---
layout: post
title: "Too Fast Causal Inference under Causal Insufficiency"
date: 2018-05-30 19:32:39
categories: arXiv_AI
tags: arXiv_AI Attention Inference
author: Mieczys&#x142;aw A. K&#x142;opotek
mathjax: true
---

* content
{:toc}

##### Abstract
Causally insufficient structures (models with latent or hidden variables, or with confounding etc.) of joint probability distributions have been subject of intense study not only in statistics, but also in various AI systems. In AI, belief networks, being representations of joint probability distribution with an underlying directed acyclic graph structure, are paid special attention due to the fact that efficient reasoning (uncertainty propagation) methods have been developed for belief network structures. Algorithms have been therefore developed to acquire the belief network structure from data. As artifacts due to variable hiding negatively influence the performance of derived belief networks, models with latent variables have been studied and several algorithms for learning belief network structure under causal insufficiency have also been developed. 
 Regrettably, some of them are known already to be erroneous (e.g. IC algorithm of [Pearl:Verma:91]. This paper is devoted to another algorithm, the Fast Causal Inference (FCI) Algorithm of [Spirtes:93]. It is proven by a specially constructed example that this algorithm, as it stands in [Spirtes:93], is also erroneous. Fundamental reason for failure of this algorithm is the temporary introduction of non-real links between nodes of the network with the intention of later removal. While for trivial dependency structures these non-real links may be actually removed, this may not be the case for complex ones, e.g. for the case described in this paper. A remedy of this failure is proposed.

##### Abstract (translated by Google)
由于联合概率分布的结构不足（结构隐含变量或隐含变量的模型），不仅在统计学上，而且在各种人工智能系统中都受到密切研究。在AI中，信念网络作为具有基础有向无环图结构的联合概率分布的表示，由于已经为信念网络结构开发了有效的推理（不确定传播）方法，因此受到特别关注。因此已经开发了用于从数据获取信念网络结构的算法。由于变量隐藏产生的文物对导出的信任网络的性能产生负面影响，因此研究了潜在变量的模型，并研究了因果关系不足下学习信念网络结构的几种算法。
 令人遗憾的是，其中一些已知是错误的（例如[Pearl：Verma：91]的IC算法）。本文致力于另一种算法，[Spirtes：93]的快速因果推断（FCI）算法。通过一个特别构造的例子，这个算法，就像它在[Spirtes：93]中所表示的那样，也是错误的。该算法失败的根本原因是临时引入网络节点之间的非实际链接，以便以后去除。虽然对于琐碎的依赖性结构，这些非实际的链接可能实际上被删除，但对于复杂的链接可能并非如此，例如本文中描述的情况。

##### URL
[http://arxiv.org/abs/1806.00352](http://arxiv.org/abs/1806.00352)

##### PDF
[http://arxiv.org/pdf/1806.00352](http://arxiv.org/pdf/1806.00352)

