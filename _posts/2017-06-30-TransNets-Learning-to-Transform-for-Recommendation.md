---
layout: post
title: "TransNets: Learning to Transform for Recommendation"
date: 2017-06-30 15:14:22
categories: arXiv_CL
tags: arXiv_CL Review Deep_Learning Recommendation
author: Rose Catherine, William Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep learning methods have been shown to improve the performance of recommender systems over traditional methods, especially when review text is available. For example, a recent model, DeepCoNN, uses neural nets to learn one latent representation for the text of all reviews written by a target user, and a second latent representation for the text of all reviews for a target item, and then combines these latent representations to obtain state-of-the-art performance on recommendation tasks. We show that (unsurprisingly) much of the predictive value of review text comes from reviews of the target user for the target item. We then introduce a way in which this information can be used in recommendation, even when the target user's review for the target item is not available. Our model, called TransNets, extends the DeepCoNN model by introducing an additional latent layer representing the target user-target item pair. We then regularize this layer, at training time, to be similar to another latent representation of the target user's review of the target item. We show that TransNets and extensions of it improve substantially over the previous state-of-the-art.

##### Abstract (translated by Google)
最近，深度学习方法已经被证明可以提高推荐系统的性能，而传统的方法尤其是在有评论文本的情况下。例如，最近的一个模型DeepCoNN使用神经网络来学习目标用户所写的所有评论的文本的一个潜在表示，以及针对目标项目的所有评论的文本的第二潜在表示，然后将这些潜在在推荐工作中获得最新的表现。我们显示（不出所料）评论文本的预测价值的大部分来自目标用户对目标项目的评论。然后，我们介绍一种可以在推荐中使用此信息的方式，即使目标用户对目标项目的评论不可用。我们的模型叫做TransNetets，通过引入一个代表目标用户 - 目标物品对的附加潜在层来扩展DeepCoNN模型。然后，我们在训练时间调整这个层次，以类似于目标用户对目标项目的审查的另一个潜在表示。我们展示了TransNet和它的扩展大大改善了先前的状态。

##### URL
[https://arxiv.org/abs/1704.02298](https://arxiv.org/abs/1704.02298)

##### PDF
[https://arxiv.org/pdf/1704.02298](https://arxiv.org/pdf/1704.02298)

