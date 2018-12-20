---
layout: post
title: "Universal Successor Features Approximators"
date: 2018-12-18 20:01:41
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Inference
author: Diana Borsa, Andr&#xe9; Barreto, John Quan, Daniel Mankowitz, R&#xe9;mi Munos, Hado van Hasselt, David Silver, Tom Schaul
mathjax: true
---

* content
{:toc}

##### Abstract
The ability of a reinforcement learning (RL) agent to learn about many reward functions at the same time has many potential benefits, such as the decomposition of complex tasks into simpler ones, the exchange of information between tasks, and the reuse of skills. We focus on one aspect in particular, namely the ability to generalise to unseen tasks. Parametric generalisation relies on the interpolation power of a function approximator that is given the task description as input; one of its most common form are universal value function approximators (UVFAs). Another way to generalise to new tasks is to exploit structure in the RL problem itself. Generalised policy improvement (GPI) combines solutions of previous tasks into a policy for the unseen task; this relies on instantaneous policy evaluation of old policies under the new reward function, which is made possible through successor features (SFs). Our proposed universal successor features approximators (USFAs) combine the advantages of all of these, namely the scalability of UVFAs, the instant inference of SFs, and the strong generalisation of GPI. We discuss the challenges involved in training a USFA, its generalisation properties and demonstrate its practical benefits and transfer abilities on a large-scale domain in which the agent has to navigate in a first-person perspective three-dimensional environment.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07626](http://arxiv.org/abs/1812.07626)

##### PDF
[http://arxiv.org/pdf/1812.07626](http://arxiv.org/pdf/1812.07626)

