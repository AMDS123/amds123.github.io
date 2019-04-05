---
layout: post
title: "Self-Adapting Goals Allow Transfer of Predictive Models to New Tasks"
date: 2019-04-04 09:52:18
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning
author: Kai Olav Ellefsen, Jim Torresen
mathjax: true
---

* content
{:toc}

##### Abstract
A long-standing challenge in Reinforcement Learning is enabling agents to learn a model of their environment which can be transferred to solve other problems in a world with the same underlying rules. One reason this is difficult is the challenge of learning accurate models of an environment. If such a model is inaccurate, the agent's plans and actions will likely be sub-optimal, and likely lead to the wrong outcomes. Recent progress in model-based reinforcement learning has improved the ability for agents to learn and use predictive models. In this paper, we extend a recent deep learning architecture which learns a predictive model of the environment that aims to predict only the value of a few key measurements, which are be indicative of an agent's performance. Predicting only a few measurements rather than the entire future state of an environment makes it more feasible to learn a valuable predictive model. We extend this predictive model with a small, evolving neural network that suggests the best goals to pursue in the current state. We demonstrate that this allows the predictive model to transfer to new scenarios where goals are different, and that the adaptive goals can even adjust agent behavior on-line, changing its strategy to fit the current context.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02435](http://arxiv.org/abs/1904.02435)

##### PDF
[http://arxiv.org/pdf/1904.02435](http://arxiv.org/pdf/1904.02435)

