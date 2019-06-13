---
layout: post
title: "DualDICE: Behavior-Agnostic Estimation of Discounted Stationary Distribution Corrections"
date: 2019-06-10 19:33:00
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Optimization
author: Ofir Nachum, Yinlam Chow, Bo Dai, Lihong Li
mathjax: true
---

* content
{:toc}

##### Abstract
In many real-world reinforcement learning applications, access to the environment is limited to a fixed dataset, instead of direct (online) interaction with the environment. When using this data for either evaluation or training of a new policy, accurate estimates of discounted stationary distribution ratios -- correction terms which quantify the likelihood that the new policy will experience a certain state-action pair normalized by the probability with which the state-action pair appears in the dataset -- can improve accuracy and performance. In this work, we propose an algorithm, DualDICE, for estimating these quantities. In contrast to previous approaches, our algorithm is agnostic to knowledge of the behavior policy (or policies) used to generate the dataset. Furthermore, it eschews any direct use of importance weights, thus avoiding potential optimization instabilities endemic of previous methods. In addition to providing theoretical guarantees, we present an empirical study of our algorithm applied to off-policy policy evaluation and find that our algorithm significantly improves accuracy compared to existing techniques.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04733](http://arxiv.org/abs/1906.04733)

##### PDF
[http://arxiv.org/pdf/1906.04733](http://arxiv.org/pdf/1906.04733)

