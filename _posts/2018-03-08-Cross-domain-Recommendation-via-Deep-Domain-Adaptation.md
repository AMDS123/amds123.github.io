---
layout: post
title: "Cross-domain Recommendation via Deep Domain Adaptation"
date: 2018-03-08 09:43:04
categories: arXiv_CL
tags: arXiv_CL Classification Relation Recommendation
author: Heishiro Kanagawa, Hayato Kobayashi, Nobuyuki Shimizu, Yukihiro Tagami, Taiji Suzuki
mathjax: true
---

* content
{:toc}

##### Abstract
The behavior of users in certain services could be a clue that can be used to infer their preferences and may be used to make recommendations for other services they have never used. However, the cross-domain relationships between items and user consumption patterns are not simple, especially when there are few or no common users and items across domains. To address this problem, we propose a content-based cross-domain recommendation method for cold-start users that does not require user- and item- overlap. We formulate recommendation as extreme multi-class classification where labels (items) corresponding to the users are predicted. With this formulation, the problem is reduced to a domain adaptation setting, in which a classifier trained in the source domain is adapted to the target domain. For this, we construct a neural network that combines an architecture for domain adaptation, Domain Separation Network, with a denoising autoencoder for item representation. We assess the performance of our approach in experiments on a pair of data sets collected from movie and news services of Yahoo! JAPAN and show that our approach outperforms several baseline methods including a cross-domain collaborative filtering method.

##### Abstract (translated by Google)
用户在某些服务中的行为可能是一条线索，可用于推断其偏好，并可用于为其他从未使用过的服务提供建议。但是，项目与用户消费模式之间的跨域关系并不简单，尤其是跨域的普通用户和项目很少或没有时。为了解决这个问题，我们针对冷启动用户提出了一种基于内容的跨域推荐方法，该方法不需要用户和项目重叠。我们将建议制定为预测与用户对应的标签（项目）的极端多类别分类。通过这个公式，问题被简化为一个域适应设置，其中在源域中训练的分类器适应于目标域。为此，我们构建了一个神经网络，该网络将领域适应的架构，领域分离网络与用于项目表示的去噪自动编码器相结合。我们评估了我们的方法在从雅虎电影和新闻服务收集的一组数据集上的实验性能。并表明我们的方法胜过了几种基准方法，包括跨域协作过滤方法。

##### URL
[http://arxiv.org/abs/1803.03018](http://arxiv.org/abs/1803.03018)

##### PDF
[http://arxiv.org/pdf/1803.03018](http://arxiv.org/pdf/1803.03018)

