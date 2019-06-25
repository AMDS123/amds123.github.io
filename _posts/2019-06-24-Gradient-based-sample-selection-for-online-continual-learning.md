---
layout: post
title: "Gradient based sample selection for online continual learning"
date: 2019-06-24 09:00:19
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Rahaf Aljundi, Min Lin, Baptiste Goujaud, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
A continual learning agent learns online with a non-stationary and never-ending stream of data. The key to such learning process is to overcome the catastrophic forgetting of previously seen data, which is a well known problem of neural networks. To prevent forgetting, a replay buffer is usually employed to store the previous data for the purpose of rehearsal. Previous works often depend on task boundary and i.i.d. assumptions to properly select samples for the replay buffer. In this work, we formulate sample selection as a constraint reduction problem based on the constrained optimization view of continual learning. The goal is to select a fixed subset of constraints that best approximate the feasible region defined by the original constraints. We show that it is equivalent to maximizing the diversity of samples in the replay buffer with parameters gradient as the feature. We further develop a greedy alternative that is cheap and efficient. The advantage of the proposed method is demonstrated by comparing to other alternatives under the continual learning setting. Further comparisons are made against state of the art methods that rely on task boundaries which show comparable or even better results for our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08671](http://arxiv.org/abs/1903.08671)

##### PDF
[http://arxiv.org/pdf/1903.08671](http://arxiv.org/pdf/1903.08671)

