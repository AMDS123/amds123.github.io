---
layout: post
title: "A survey on policy search algorithms for learning robot controllers in a handful of trials"
date: 2019-05-31 22:22:44
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Survey Optimization
author: Konstantinos Chatzilygeroudis, Vassilis Vassiliades, Freek Stulp, Sylvain Calinon, Jean-Baptiste Mouret
mathjax: true
---

* content
{:toc}

##### Abstract
Most policy search algorithms require thousands of training episodes to find an effective policy, which is often infeasible with a physical robot. This survey article focuses on the extreme other end of the spectrum: how can a robot adapt with only a handful of trials (a dozen) and a few minutes? By analogy with the word "big-data", we refer to this challenge as "micro-data reinforcement learning". We show that a first strategy is to leverage prior knowledge on the policy structure (e.g., dynamic movement primitives), on the policy parameters (e.g., demonstrations), or on the dynamics (e.g., simulators). A second strategy is to create data-driven surrogate models of the expected reward (e.g., Bayesian optimization) or the dynamical model (e.g., model-based policy search), so that the policy optimizer queries the model instead of the real system. Overall, all successful micro-data algorithms combine these two strategies by varying the kind of model and prior knowledge. The current scientific challenges essentially revolve around scaling up to complex robots (e.g., humanoids), designing generic priors, and optimizing the computing time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.02303](http://arxiv.org/abs/1807.02303)

##### PDF
[http://arxiv.org/pdf/1807.02303](http://arxiv.org/pdf/1807.02303)

