---
layout: post
title: "Robust Federated Training via Collaborative Machine Teaching using Trusted Instances"
date: 2019-05-08 07:27:04
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Yufei Han, Xiangliang Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Federated learning performs distributed model training using local data hosted by agents. It shares only model parameter updates for iterative aggregation at the server. Although it is privacy-preserving by design, federated learning is vulnerable to noise corruption of local agents, as demonstrated in the previous study on adversarial data poisoning threat against federated learning systems. Even a single noise-corrupted agent can bias the model training. In our work, we propose a collaborative and privacy-preserving machine teaching paradigm with multiple distributed teachers, to improve robustness of the federated training process against local data corruption. We assume that each local agent (teacher) have the resources to verify a small portions of trusted instances, which may not by itself be adequate for learning. In the proposed collaborative machine teaching method, these trusted instances guide the distributed agents to jointly select a compact while informative training subset from data hosted by their own. Simultaneously, the agents learn to add changes of limited magnitudes into the selected data instances, in order to improve the testing performances of the federally trained model despite of the training data corruption. Experiments on toy and real data demonstrate that our approach can identify training set bugs effectively and suggest appropriate changes to the labels. Our algorithm is a step toward trustworthy machine learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02941](http://arxiv.org/abs/1905.02941)

##### PDF
[http://arxiv.org/pdf/1905.02941](http://arxiv.org/pdf/1905.02941)

