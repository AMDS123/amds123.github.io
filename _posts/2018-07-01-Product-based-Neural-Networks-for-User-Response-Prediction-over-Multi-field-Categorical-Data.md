---
layout: post
title: "Product-based Neural Networks for User Response Prediction over Multi-field Categorical Data"
date: 2018-07-01 11:02:50
categories: arXiv_CV
tags: arXiv_CV Sparse Attention Optimization Prediction Recommendation
author: Yanru Qu, Bohui Fang, Weinan Zhang, Ruiming Tang, Minzhe Niu, Huifeng Guo, Yong Yu, Xiuqiang He
mathjax: true
---

* content
{:toc}

##### Abstract
User response prediction is a crucial component for personalized information retrieval and filtering scenarios, such as recommender system and web search. The data in user response prediction is mostly in a multi-field categorical format and transformed into sparse representations via one-hot encoding. Due to the sparsity problems in representation and optimization, most research focuses on feature engineering and shallow modeling. Recently, deep neural networks have attracted research attention on such a problem for their high capacity and end-to-end training scheme. In this paper, we study user response prediction in the scenario of click prediction. We first analyze a coupled gradient issue in latent vector-based models and propose kernel product to learn field-aware feature interactions. Then we discuss an insensitive gradient issue in DNN-based models and propose Product-based Neural Network (PNN) which adopts a feature extractor to explore feature interactions. Generalizing the kernel product to a net-in-net architecture, we further propose Product-network In Network (PIN) which can generalize previous models. Extensive experiments on 4 industrial datasets and 1 contest dataset demonstrate that our models consistently outperform 8 baselines on both AUC and log loss. Besides, PIN makes great CTR improvement (relatively 34.67%) in online A/B test.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.00311](https://arxiv.org/abs/1807.00311)

##### PDF
[https://arxiv.org/pdf/1807.00311](https://arxiv.org/pdf/1807.00311)

