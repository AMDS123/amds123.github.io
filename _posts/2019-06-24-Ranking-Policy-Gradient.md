---
layout: post
title: "Ranking Policy Gradient"
date: 2019-06-24 00:13:42
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Kaixiang Lin, Jiayu Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Sample inefficiency is a long-lasting problem in reinforcement learning (RL). The state-of-the-art uses value function to derive policy while it usually requires an extensive search over the state-action space, which is one reason for the inefficiency. Towards the sample-efficient RL, we propose ranking policy gradient (RPG), a policy gradient method that learns the optimal ranking of a set of discrete actions. To accelerate the learning of policy gradient methods, we describe a novel off-policy learning framework and establish the equivalence between maximizing the lower bound of return and imitating a near-optimal policy without accessing any oracles. These results lead to a general sample-efficient off-policy learning framework, which accelerates learning and reduces variance. Furthermore, the sample complexity of RPG does not depend on the dimension of state space, which enables RPG for large-scale problems. We conduct extensive experiments showing that when consolidating with the off-policy learning framework, RPG substantially reduces the sample complexity, comparing to the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09674](http://arxiv.org/abs/1906.09674)

##### PDF
[http://arxiv.org/pdf/1906.09674](http://arxiv.org/pdf/1906.09674)

