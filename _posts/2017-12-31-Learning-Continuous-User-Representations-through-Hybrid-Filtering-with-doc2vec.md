---
layout: post
title: "Learning Continuous User Representations through Hybrid Filtering with doc2vec"
date: 2017-12-31 00:51:56
categories: arXiv_AI
tags: arXiv_AI Language_Model Recommendation
author: Simon Stiebellehner, Jun Wang, Shuai Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Players in the online ad ecosystem are struggling to acquire the user data required for precise targeting. Audience look-alike modeling has the potential to alleviate this issue, but models' performance strongly depends on quantity and quality of available data. In order to maximize the predictive performance of our look-alike modeling algorithms, we propose two novel hybrid filtering techniques that utilize the recent neural probabilistic language model algorithm doc2vec. We apply these methods to data from a large mobile ad exchange and additional app metadata acquired from the Apple App store and Google Play store. First, we model mobile app users through their app usage histories and app descriptions (user2vec). Second, we introduce context awareness to that model by incorporating additional user and app-related metadata in model training (context2vec). Our findings are threefold: (1) the quality of recommendations provided by user2vec is notably higher than current state-of-the-art techniques. (2) User representations generated through hybrid filtering using doc2vec prove to be highly valuable features in supervised machine learning models for look-alike modeling. This represents the first application of hybrid filtering user models using neural probabilistic language models, specifically doc2vec, in look-alike modeling. (3) Incorporating context metadata in the doc2vec model training process to introduce context awareness has positive effects on performance and is superior to directly including the data as features in the downstream supervised models.

##### Abstract (translated by Google)
在线广告生态系统中的玩家正在努力获取精确定位所需的用户数据。观众相似的建模有可能缓解这个问题，但模型的性能在很大程度上取决于可用数据的数量和质量。为了最大化我们的相似建模算法的预测性能，我们提出了两种新颖的混合滤波技术，它们利用了最近的神经概率语言模型算法doc2vec。我们将这些方法应用于来自大型移动广告交易平台的数据以及从Apple App Store和Google Play商店中获取的其他应用元数据。首先，我们通过应用程序使用历史记录和应用程序描述（user2vec）为移动应用程序用户建模。其次，通过在模型训练（context2vec）中引入额外的用户和应用程序相关的元数据，我们将情境感知引入到该模型中。我们的研究结果有三个：（1）user2vec提供的建议的质量明显高于当前的最新技术。 （2）使用doc2vec通过混合过滤产生的用户表示被证明是监督机器学习模型中非常有价值的特征，用于相似建模。这代表了使用神经概率语言模型，特别是doc2vec，在类似建模中的混合过滤用户模型的第一个应用。 （3）将上下文元数据引入到doc2vec模型训练过程中，引入上下文感知对性能有正向影响，优于直接将数据作为下一个监督模型的特征。

##### URL
[http://arxiv.org/abs/1801.00215](http://arxiv.org/abs/1801.00215)

##### PDF
[http://arxiv.org/pdf/1801.00215](http://arxiv.org/pdf/1801.00215)

