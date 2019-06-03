---
layout: post
title: "Combating the Compounding-Error Problem with a Multi-step Model"
date: 2019-05-30 21:30:29
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: Kavosh Asadi, Dipendra Misra, Seungchan Kim, Michel L. Littman
mathjax: true
---

* content
{:toc}

##### Abstract
Model-based reinforcement learning is an appealing framework for creating agents that learn, plan, and act in sequential environments. Model-based algorithms typically involve learning a transition model that takes a state and an action and outputs the next state---a one-step model. This model can be composed with itself to enable predicting multiple steps into the future, but one-step prediction errors can get magnified, leading to unacceptable inaccuracy. This compounding-error problem plagues planning and undermines model-based reinforcement learning. In this paper, we address the compounding-error problem by introducing a multi-step model that directly outputs the outcome of executing a sequence of actions. Novel theoretical and empirical results indicate that the multi-step model is more conducive to efficient value-function estimation, and it yields better action selection compared to the one-step model. These results make a strong case for using multi-step models in the context of model-based reinforcement learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13320](http://arxiv.org/abs/1905.13320)

##### PDF
[http://arxiv.org/pdf/1905.13320](http://arxiv.org/pdf/1905.13320)

