---
layout: post
title: "GCN-LASE: Towards Adequately Incorporating Link Attributes in Graph Convolutional Networks"
date: 2019-02-26 09:21:27
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Ziyao Li, Liang Zhang, Guojie Song
mathjax: true
---

* content
{:toc}

##### Abstract
Graph Convolutional Networks (GCNs) have proved to be a most powerful architecture in aggregating local neighborhood information for individual graph nodes. Low-rank proximities and node features are successfully leveraged in existing GCNs, however, attributes that graph links may carry are commonly ignored, as almost all of these models simplify graph links into binary or scalar values describing node connectedness. In our paper instead, links are reverted to hypostatic relationships between entities with descriptional attributes. We propose GCN-LASE (GCN with Link Attributes and Sampling Estimation), a novel GCN model taking both node and link attributes as inputs. To adequately captures the interactions between link and node attributes, their tensor product is used as neighbor features, based on which we define several graph kernels and further develop according architectures for LASE. Besides, to accelerate the training process, the sum of features in entire neighborhoods are estimated through Monte Carlo method, with novel sampling strategies designed for LASE to minimize the estimation variance. Our experiments show that LASE outperforms strong baselines over various graph datasets, and further experiments corroborate the informativeness of link attributes and our model's ability of adequately leveraging them.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09817](http://arxiv.org/abs/1902.09817)

##### PDF
[http://arxiv.org/pdf/1902.09817](http://arxiv.org/pdf/1902.09817)

