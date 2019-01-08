---
layout: post
title: "A* Tree Search for Portfolio Management"
date: 2019-01-07 14:59:15
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Xiaojie Gao, Shikui Tu, Lei Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a planning-based method to teach an agent to manage portfolio from scratch. Our approach combines deep reinforcement learning techniques with search techniques like AlphaGo. By uniting the advantages in A* search algorithm with Monte Carlo tree search, we come up with a new algorithm named A* tree search in which best information is returned to guide next search. Also, the expansion mode of Monte Carlo tree is improved for a higher utilization of the neural network. The suggested algorithm can also optimize non-differentiable utility function by combinatorial search. This technique is then used in our trading system. The major component is a neural network that is trained by trading experiences from tree search and outputs prior probability to guide search by pruning away branches in turn. Experimental results on simulated and real financial data verify the robustness of the proposed trading system and the trading system produces better strategies than several approaches based on reinforcement learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01855](http://arxiv.org/abs/1901.01855)

##### PDF
[http://arxiv.org/pdf/1901.01855](http://arxiv.org/pdf/1901.01855)

