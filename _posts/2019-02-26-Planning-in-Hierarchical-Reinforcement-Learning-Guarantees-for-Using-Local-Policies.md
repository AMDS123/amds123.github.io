---
layout: post
title: "Planning in Hierarchical Reinforcement Learning: Guarantees for Using Local Policies"
date: 2019-02-26 15:04:18
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Tom Zahavy, Avinatan Hasidim, Haim Kaplan, Yishay Mansour
mathjax: true
---

* content
{:toc}

##### Abstract
We consider a settings of hierarchical reinforcement learning, in which the reward is a sum of components. For each component we are given a policy that maximizes it and our goal is to assemble a policy from the individual policies that maximizes the sum of the components. We provide theoretical guarantees for assembling such policies in deterministic MDPs with collectible rewards. Our approach builds on formulating this problem as a traveling salesman problem with discounted reward. We focus on local solutions, i.e., policies that only use information from the current state; thus, they are easy to implement and do not require substantial computational resources. We propose three local stochastic policies and prove that they guarantee better performance than any deterministic local policy in the worst case; experimental results suggest that they also perform better on average.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10140](http://arxiv.org/abs/1902.10140)

##### PDF
[http://arxiv.org/pdf/1902.10140](http://arxiv.org/pdf/1902.10140)

