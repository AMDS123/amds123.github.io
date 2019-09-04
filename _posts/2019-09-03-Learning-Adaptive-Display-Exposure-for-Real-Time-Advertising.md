---
layout: post
title: "Learning Adaptive Display Exposure for Real-Time Advertising"
date: 2019-09-03 01:55:56
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Recommendation
author: Weixun Wang, Junqi Jin, Jianye Hao, Chunjie Chen, Chuan Yu, Weinan Zhang, Jun Wang, Xiaotian Hao, Yixi Wang, Han Li, Jian Xu, Kun Gai
mathjax: true
---

* content
{:toc}

##### Abstract
In E-commerce advertising, where product recommendations and product ads are presented to users simultaneously, the traditional setting is to display ads at fixed positions. However, under such a setting, the advertising system loses the flexibility to control the number and positions of ads, resulting in sub-optimal platform revenue and user experience. Consequently, major e-commerce platforms (e.g., Taobao.com) have begun to consider more flexible ways to display ads. In this paper, we investigate the problem of advertising with adaptive exposure: can we dynamically determine the number and positions of ads for each user visit under certain business constraints so that the platform revenue can be increased? More specifically, we consider two types of constraints: request-level constraint ensures user experience for each user visit, and platform-level constraint controls the overall platform monetization rate. We model this problem as a Constrained Markov Decision Process with per-state constraint (psCMDP) and propose a constrained two-level reinforcement learning approach to decompose the original problem into two relatively independent sub-problems. To accelerate policy learning, we also devise a constrained hindsight experience replay mechanism. Experimental evaluations on industry-scale real-world datasets demonstrate the merits of our approach in both obtaining higher revenue under the constraints and the effectiveness of the constrained hindsight experience replay mechanism.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.03149](http://arxiv.org/abs/1809.03149)

##### PDF
[http://arxiv.org/pdf/1809.03149](http://arxiv.org/pdf/1809.03149)

