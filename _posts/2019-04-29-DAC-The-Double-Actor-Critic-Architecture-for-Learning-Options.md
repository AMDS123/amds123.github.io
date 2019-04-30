---
layout: post
title: "DAC: The Double Actor-Critic Architecture for Learning Options"
date: 2019-04-29 14:57:47
categories: arXiv_AI
tags: arXiv_AI Transfer_Learning Optimization
author: Shangtong Zhang, Shimon Whiteson
mathjax: true
---

* content
{:toc}

##### Abstract
We reformulate the option framework as two parallel augmented MDPs. Under this novel formulation, all policy optimization algorithms can be used off the shelf to learn intra-option policies, option termination conditions, and a master policy over options. We apply an actor-critic algorithm on each augmented MDP, yielding the Double Actor-Critic (DAC) architecture. Furthermore, we show that, when state-value functions are used as critics, one critic can be expressed in terms of the other, and hence only one critic is necessary. Our experiments on challenging robot simulation tasks demonstrate that DAC outperforms previous gradient-based option learning algorithms by a large margin and significantly outperforms its hierarchy-free counterparts in a transfer learning setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12691](http://arxiv.org/abs/1904.12691)

##### PDF
[http://arxiv.org/pdf/1904.12691](http://arxiv.org/pdf/1904.12691)

