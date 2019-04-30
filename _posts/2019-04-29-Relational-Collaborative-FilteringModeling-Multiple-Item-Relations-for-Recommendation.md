---
layout: post
title: "Relational Collaborative Filtering:Modeling Multiple Item Relations for Recommendation"
date: 2019-04-29 16:20:23
categories: arXiv_AI
tags: arXiv_AI Knowledge Attention Embedding Relation Recommendation
author: Xin Xin, Xiangnan He, Yongfeng Zhang, Yongdong Zhang, Joemon Jose
mathjax: true
---

* content
{:toc}

##### Abstract
Existing item-based collaborative filtering (ICF) methods leverage only the relation of collaborative similarity. Nevertheless, there exist multiple relations between items in real-world scenarios. Distinct from the collaborative similarity that implies co-interact patterns from the user perspective, these relations reveal fine-grained knowledge on items from different perspectives of meta-data, functionality, etc. However, how to incorporate multiple item relations is less explored in recommendation research. In this work, we propose Relational Collaborative Filtering (RCF), a general framework to exploit multiple relations between items in recommender system. We find that both the relation type and the relation value are crucial in inferring user preference. To this end, we develop a two-level hierarchical attention mechanism to model user preference. The first-level attention discriminates which types of relations are more important, and the second-level attention considers the specific relation values to estimate the contribution of a historical item in recommending the target item. To make the item embeddings be reflective of the relational structure between items, we further formulate a task to preserve the item relations, and jointly train it with the recommendation task of preference modeling. Empirical results on two real datasets demonstrate the strong performance of RCF. Furthermore, we also conduct qualitative analyses to show the benefits of explanations brought by the modeling of multiple item relations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12796](http://arxiv.org/abs/1904.12796)

##### PDF
[http://arxiv.org/pdf/1904.12796](http://arxiv.org/pdf/1904.12796)

