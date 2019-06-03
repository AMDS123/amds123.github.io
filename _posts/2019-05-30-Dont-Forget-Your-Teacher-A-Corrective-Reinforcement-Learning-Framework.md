---
layout: post
title: "Don't Forget Your Teacher: A Corrective Reinforcement Learning Framework"
date: 2019-05-30 01:47:18
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Mohammadreza Nazari, Majid Jahani, Lawrence V. Snyder, Martin Tak&#xe1;&#x10d;
mathjax: true
---

* content
{:toc}

##### Abstract
Although reinforcement learning (RL) can provide reliable solutions in many settings, practitioners are often wary of the discrepancies between the RL solution and their status quo procedures. Therefore, they may be reluctant to adapt to the novel way of executing tasks proposed by RL. On the other hand, many real-world problems require relatively small adjustments from the status quo policies to achieve improved performance. Therefore, we propose a student-teacher RL mechanism in which the RL (the "student") learns to maximize its reward, subject to a constraint that bounds the difference between the RL policy and the "teacher" policy. The teacher can be another RL policy (e.g., trained under a slightly different setting), the status quo policy, or any other exogenous policy. We formulate this problem using a stochastic optimization model and solve it using a primal-dual policy gradient algorithm. We prove that the policy is asymptotically optimal. However, a naive implementation suffers from high variance and convergence to a stochastic optimal policy. With a few practical adjustments to address these issues, our numerical experiments confirm the effectiveness of our proposed method in multiple GridWorld scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13562](http://arxiv.org/abs/1905.13562)

##### PDF
[http://arxiv.org/pdf/1905.13562](http://arxiv.org/pdf/1905.13562)

