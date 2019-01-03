---
layout: post
title: "Opportunistic Learning: Budgeted Cost-Sensitive Learning from Data Streams"
date: 2019-01-02 02:33:54
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Classification Prediction
author: Mohammad Kachuee, Orpaz Goldstein, Kimmo Karkkainen, Sajad Darabi, Majid Sarrafzadeh
mathjax: true
---

* content
{:toc}

##### Abstract
In many real-world learning scenarios, features are only acquirable at a cost constrained under a budget. In this paper, we propose a novel approach for cost-sensitive feature acquisition at the prediction-time. The suggested method acquires features incrementally based on a context-aware feature-value function. We formulate the problem in the reinforcement learning paradigm, and introduce a reward function based on the utility of each feature. Specifically, MC dropout sampling is used to measure expected variations of the model uncertainty which is used as a feature-value function. Furthermore, we suggest sharing representations between the class predictor and value function estimator networks. The suggested approach is completely online and is readily applicable to stream learning setups. The solution is evaluated on three different datasets including the well-known MNIST dataset as a benchmark as well as two cost-sensitive datasets: Yahoo Learning to Rank and a dataset in the medical domain for diabetes classification. According to the results, the proposed method is able to efficiently acquire features and make accurate predictions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.00243](https://arxiv.org/abs/1901.00243)

##### PDF
[https://arxiv.org/pdf/1901.00243](https://arxiv.org/pdf/1901.00243)

