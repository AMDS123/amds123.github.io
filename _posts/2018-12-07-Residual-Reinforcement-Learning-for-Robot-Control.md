---
layout: post
title: "Residual Reinforcement Learning for Robot Control"
date: 2018-12-07 20:10:23
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Tobias Johannink, Shikhar Bahl, Ashvin Nair, Jianlan Luo, Avinash Kumar, Matthias Loskyll, Juan Aparicio Ojea, Eugen Solowjow, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional feedback control methods can solve various types of robot control problems very efficiently by capturing the structure with explicit models, such as rigid body equations of motion. However, many control problems in modern manufacturing deal with contacts and friction, which are difficult to capture with first-order physical modeling. Hence, applying control design methodologies to these kinds of problems often results in brittle and inaccurate controllers, which have to be manually tuned for deployment. Reinforcement learning (RL) methods have been demonstrated to be capable of learning continuous robot controllers from interactions with the environment, even for problems that include friction and contacts. In this paper, we study how we can solve difficult control problems in the real world by decomposing them into a part that is solved efficiently by conventional feedback control methods, and the residual which is solved with RL. The final control policy is a superposition of both control signals. We demonstrate our approach by training an agent to successfully perform a real-world block assembly task involving contacts and unstable objects.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03201](http://arxiv.org/abs/1812.03201)

##### PDF
[http://arxiv.org/pdf/1812.03201](http://arxiv.org/pdf/1812.03201)

