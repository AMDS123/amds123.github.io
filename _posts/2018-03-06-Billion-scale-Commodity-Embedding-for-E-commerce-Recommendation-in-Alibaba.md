---
layout: post
title: "Billion-scale Commodity Embedding for E-commerce Recommendation in Alibaba"
date: 2018-03-06 05:20:14
categories: arXiv_AI
tags: arXiv_AI Embedding Recommendation
author: Jizhe Wang, Pipei Huang, Huan Zhao, Zhibo Zhang, Binqiang Zhao, Dik Lun Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Recommender systems (RSs) have been the most important technology for increasing the business in Taobao, the largest online consumer-to-consumer (C2C) platform in China. The billion-scale data in Taobao creates three major challenges to Taobao's RS: scalability, sparsity and cold start. In this paper, we present our technical solutions to address these three challenges. The methods are based on the graph embedding framework. We first construct an item graph from users' behavior history. Each item is then represented as a vector using graph embedding. The item embeddings are employed to compute pairwise similarities between all items, which are then used in the recommendation process. To alleviate the sparsity and cold start problems, side information is incorporated into the embedding framework. We propose two aggregation methods to integrate the embeddings of items and the corresponding side information. Experimental results from offline experiments show that methods incorporating side information are superior to those that do not. Further, we describe the platform upon which the embedding methods are deployed and the workflow to process the billion-scale data in Taobao. Using online A/B test, we show that the online Click-Through-Rate (CTRs) are improved comparing to the previous recommendation methods widely used in Taobao, further demonstrating the effectiveness and feasibility of our proposed methods in Taobao's live production environment.

##### Abstract (translated by Google)
推荐系统（RS）一直是增加中国最大的在线消费者对消费者（C2C）平台淘宝业务的最重要技术。淘宝的数十亿数据为淘宝网的RS带来三大挑战：可扩展性，稀缺性和冷启动。在本文中，我们提出了解决这三个难题的技术解决方案。这些方法基于图嵌入框架。我们首先根据用户的行为历史构建一个项目图。然后使用图嵌入将每个项目表示为矢量。项目嵌入被用来计算所有项目之间的成对相似度，然后在推荐过程中使用。为了减轻稀疏性和冷启动问题，边界信息被纳入嵌入框架。我们提出两种聚合方法来整合项目的嵌入和相应的辅助信息。离线实验的实验结果表明，结合辅助信息的方法优于那些没有辅助信息的方法。此外，我们描述了部署嵌入方法的平台以及在淘宝上处理亿量级数据的工作流程。通过在线A / B测试，我们发现在线点击率（CTR）与之前在淘宝中广泛使用的推荐方法相比有所提高，进一步证明了我们在淘宝实时制作环境中提出的方法的有效性和可行性。

##### URL
[http://arxiv.org/abs/1803.02349](http://arxiv.org/abs/1803.02349)

##### PDF
[http://arxiv.org/pdf/1803.02349](http://arxiv.org/pdf/1803.02349)

