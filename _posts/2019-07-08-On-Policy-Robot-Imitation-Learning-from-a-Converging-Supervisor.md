---
layout: post
title: "On-Policy Robot Imitation Learning from a Converging Supervisor"
date: 2019-07-08 07:02:57
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Ashwin Balakrishna, Brijen Thananjeyan, Jonathan Lee, Arsh Zahed, Felix Li, Joseph E. Gonzalez, Ken Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
Existing on-policy imitation learning algorithms, such as DAgger, assume access to a fixed supervisor. However, there are many settings where the supervisor may converge during policy learning, such as a human performing a novel task or an improving algorithmic controller. We formalize imitation learning from a "converging supervisor" and provide sublinear static and dynamic regret guarantees against the best policy in hindsight with labels from the converged supervisor, even when labels during learning are only from intermediate supervisors. We then show that this framework is closely connected to a recent class of reinforcement learning (RL) algorithms known as dual policy iteration (DPI), which alternate between training a reactive learner with imitation learning and a model-based supervisor with data from the learner. Experiments suggest that when this framework is applied with the state-of-the-art deep model-based RL algorithm PETS as an improving supervisor, it outperforms deep RL baselines on continuous control tasks and provides up to an 80-fold speedup in policy evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03423](http://arxiv.org/abs/1907.03423)

##### PDF
[http://arxiv.org/pdf/1907.03423](http://arxiv.org/pdf/1907.03423)

