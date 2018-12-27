---
layout: post
title: "Learning Not to Learn: Training Deep Neural Networks with Biased Data"
date: 2018-12-26 16:01:29
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Embedding Prediction Quantitative
author: Byungju Kim, Hyunwoo Kim, Kyungsu Kim, Sungjin Kim, Junmo Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel regularization algorithm to train deep neural networks, in which data at training time is severely biased. Since a neural network efficiently learns data distribution, a network is likely to learn the bias information to categorize input data. It leads to poor performance at test time, if the bias is, in fact, irrelevant to the categorization. In this paper, we formulate a regularization loss based on mutual information between feature embedding and bias. Based on the idea of minimizing this mutual information, we propose an iterative algorithm to unlearn the bias information. We employ an additional network to predict the bias distribution and train the network adversarially against the feature embedding network. At the end of learning, the bias prediction network is not able to predict the bias not because it is poorly trained, but because the feature embedding network successfully unlearns the bias information. We also demonstrate quantitative and qualitative experimental results which show that our algorithm effectively removes the bias information from feature embedding.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10352](http://arxiv.org/abs/1812.10352)

##### PDF
[http://arxiv.org/pdf/1812.10352](http://arxiv.org/pdf/1812.10352)

