---
layout: post
title: "Reinforcement Learning for Slate-based Recommender Systems: A Tractable Decomposition and Practical Methodology"
date: 2019-05-29 22:55:28
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Recommendation
author: Eugene Ie, Vihan Jain, Jing Wang, Sanmit Navrekar, Ritesh Agarwal, Rui Wu, Heng-Tze Cheng, Morgane Lustman, Vince Gatto, Paul Covington, Jim McFadden, Tushar Chandra, Craig Boutilier
mathjax: true
---

* content
{:toc}

##### Abstract
Most practical recommender systems focus on estimating immediate user engagement without considering the long-term effects of recommendations on user behavior. Reinforcement learning (RL) methods offer the potential to optimize recommendations for long-term user engagement. However, since users are often presented with slates of multiple items - which may have interacting effects on user choice - methods are required to deal with the combinatorics of the RL action space. In this work, we address the challenge of making slate-based recommendations to optimize long-term value using RL. Our contributions are three-fold. (i) We develop SLATEQ, a decomposition of value-based temporal-difference and Q-learning that renders RL tractable with slates. Under mild assumptions on user choice behavior, we show that the long-term value (LTV) of a slate can be decomposed into a tractable function of its component item-wise LTVs. (ii) We outline a methodology that leverages existing myopic learning-based recommenders to quickly develop a recommender that handles LTV. (iii) We demonstrate our methods in simulation, and validate the scalability of decomposed TD-learning using SLATEQ in live experiments on YouTube.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12767](http://arxiv.org/abs/1905.12767)

##### PDF
[http://arxiv.org/pdf/1905.12767](http://arxiv.org/pdf/1905.12767)

