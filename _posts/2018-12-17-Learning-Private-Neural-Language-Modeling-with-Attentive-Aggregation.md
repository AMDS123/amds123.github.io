---
layout: post
title: "Learning Private Neural Language Modeling with Attentive Aggregation"
date: 2018-12-17 23:51:58
categories: arXiv_CL
tags: arXiv_CL Attention Optimization Language_Model Prediction
author: Shaoxiong Ji, Shirui Pan, Guodong Long, Xue Li, Jing Jiang, Zi Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Mobile keyboard suggestion is typically regarded as a word-level language modeling problem. Centralized machine learning technique requires massive user data collected to train on, which may impose privacy concerns for sensitive personal typing data of users. Federated learning (FL) provides a promising approach to learning private language modeling for intelligent personalized keyboard suggestion by training models in distributed clients rather than training in a central server. To obtain a global model for prediction, existing FL algorithms simply average the client models and ignore the importance of each client during model aggregation. Furthermore, there is no optimization for learning a well-generalized global model on the central server. To solve these problems, we propose a novel model aggregation with the attention mechanism considering the contribution of clients models to the global model, together with an optimization technique during server aggregation. Our proposed attentive aggregation method minimizes the weighted distance between the server model and client models through iterative parameters updating while attends the distance between the server model and client models. Through experiments on two popular language modeling datasets and a social media dataset, our proposed method outperforms its counterparts in terms of perplexity and communication cost in most settings of comparison.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07108](http://arxiv.org/abs/1812.07108)

##### PDF
[http://arxiv.org/pdf/1812.07108](http://arxiv.org/pdf/1812.07108)

