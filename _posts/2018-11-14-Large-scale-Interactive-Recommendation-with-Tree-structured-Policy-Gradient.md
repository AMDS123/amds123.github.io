---
layout: post
title: "Large-scale Interactive Recommendation with Tree-structured Policy Gradient"
date: 2018-11-14 15:53:25
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Recommendation
author: Haokun Chen, Xinyi Dai, Han Cai, Weinan Zhang, Xuejian Wang, Ruiming Tang, Yuzhou Zhang, Yong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Reinforcement learning (RL) has recently been introduced to interactive recommender systems (IRS) because of its nature of learning from dynamic interactions and planning for long-run performance. As IRS is always with thousands of items to recommend (i.e., thousands of actions), most existing RL-based methods, however, fail to handle such a large discrete action space problem and thus become inefficient. The existing work that tries to deal with the large discrete action space problem by utilizing the deep deterministic policy gradient framework suffers from the inconsistency between the continuous action representation (the output of the actor network) and the real discrete action. To avoid such inconsistency and achieve high efficiency and recommendation effectiveness, in this paper, we propose a Tree-structured Policy Gradient Recommendation (TPGR) framework, where a balanced hierarchical clustering tree is built over the items and picking an item is formulated as seeking a path from the root to a certain leaf of the tree. Extensive experiments on carefully-designed environments based on two real-world datasets demonstrate that our model provides superior recommendation performance and significant efficiency improvement over state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05869](http://arxiv.org/abs/1811.05869)

##### PDF
[http://arxiv.org/pdf/1811.05869](http://arxiv.org/pdf/1811.05869)

