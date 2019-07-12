---
layout: post
title: "A Model-based Approach for Sample-efficient Multi-task Reinforcement Learning"
date: 2019-07-11 00:45:44
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Nicholas C. Landolfi, Garrett Thomas, Tengyu Ma
mathjax: true
---

* content
{:toc}

##### Abstract
The aim of multi-task reinforcement learning is two-fold: (1) efficiently learn by training against multiple tasks and (2) quickly adapt, using limited samples, to a variety of new tasks. In this work, the tasks correspond to reward functions for environments with the same (or similar) dynamical models. We propose to learn a dynamical model during the training process and use this model to perform sample-efficient adaptation to new tasks at test time. Our algorithm sequentially trains against several tasks. We use significantly fewer samples by performing policy optimization only in a "virtual" environment whose transitions are given by our learned dynamical model. Upon encountering a new task, we first warm-up a policy on our learned dynamical model, which requires no new samples from the environment. We then adapt the dynamical model with samples from this policy in the real environment. We evaluate our approach on several continuous control benchmarks and demonstrate its efficacy over MAML, a state-of-the-art meta-learning algorithm, on these tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04964](http://arxiv.org/abs/1907.04964)

##### PDF
[http://arxiv.org/pdf/1907.04964](http://arxiv.org/pdf/1907.04964)

