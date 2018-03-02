---
layout: post
title: "Collaborative Metric Learning Recommendation System: Application to Theatrical Movie Releases"
date: 2018-03-01 04:04:35
categories: arXiv_CL
tags: arXiv_CL Language_Model Recommendation
author: Miguel Campo, JJ Espinoza, Julie Rieger, Abhinav Taliyan
mathjax: true
---

* content
{:toc}

##### Abstract
Product recommendation systems are important for major movie studios during the movie greenlight process and as part of machine learning personalization pipelines. Collaborative Filtering (CF) models have proved to be effective at powering recommender systems for online streaming services with explicit customer feedback data. CF models do not perform well in scenarios in which feedback data is not available, in cold start situations like new product launches, and situations with markedly different customer tiers (e.g., high frequency customers vs. casual customers). Generative natural language models that create useful theme-based representations of an underlying corpus of documents can be used to represent new product descriptions, like new movie plots. When combined with CF, they have shown to increase the performance in cold start situations. Outside of those cases though in which explicit customer feedback is available, recommender engines must rely on binary purchase data, which materially degrades performance. Fortunately, purchase data can be combined with product descriptions to generate meaningful representations of products and customer trajectories in a convenient product space in which proximity represents similarity. Learning to measure the distance between points in this space can be accomplished with a deep neural network that trains on customer histories and on dense vectorizations of product descriptions. We developed a system based on Collaborative (Deep) Metric Learning (CML) to predict the purchase probabilities of new theatrical releases. We trained and evaluated the model using a large dataset of customer histories, and tested the model for a set of movies that were released outside of the training window. Initial experiments show gains relative to models that do not train on collaborative preferences.

##### Abstract (translated by Google)
在电影绿灯过程中，产品推荐系统对于主要电影公司很重要，并且是机器学习个性化管道的一部分。已经证明协作过滤（CF）模型能够为具有明确客户反馈数据的在线流服务推荐系统提供动力。在反馈数据不可用的情况下，在新产品发布等冷启动情况下，以及客户层级明显不同的情况下（如高频客户与临时客户），CF模型表现不佳。生成的自然语言模型可以用来创建有用的基于文档的语料库的基于主题的表示，以表示新的产品描述，如新的电影地块。与CF结合后，他们表现出在冷启动情况下的性能提高。除了这些情况外，尽管有明确的客户反馈，但推荐引擎必须依赖二进制购买数据，这会显着降低性能。幸运的是，购买数据可以与产品说明相结合，以在邻近度代表相似度的便利产品空间中生成有意义的产品和客户轨迹表示。学习测量这个空间中点之间的距离可以通过深入的神经网络来完成，该网络可以训练客户的历史和产品描述的密集矢量化。我们开发了一个基于协作（深度）度量学习（CML）的系统来预测新剧场发布的购买概率。我们使用客户历史的大型数据集对模型进行了训练和评估，并测试了在训练窗口之外发布的一组电影的模型。最初的实验显示，相对于没有通过协作偏好进行培训的模型，收益会增加

##### URL
[https://arxiv.org/abs/1803.00202](https://arxiv.org/abs/1803.00202)

##### PDF
[https://arxiv.org/pdf/1803.00202](https://arxiv.org/pdf/1803.00202)

