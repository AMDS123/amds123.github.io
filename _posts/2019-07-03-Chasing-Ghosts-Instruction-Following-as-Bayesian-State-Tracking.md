---
layout: post
title: "Chasing Ghosts: Instruction Following as Bayesian State Tracking"
date: 2019-07-03 16:39:05
categories: arXiv_AI
tags: arXiv_AI Tracking
author: Peter Anderson, Ayush Shrivastava, Devi Parikh, Dhruv Batra, Stefan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
A visually-grounded navigation instruction can be interpreted as a sequence of expected observations and actions an agent following the correct trajectory would encounter and perform. Based on this intuition, we formulate the problem of finding the goal location in Vision-And-Language Navigation (VLN) within the framework of Bayesian state tracking - learning observation and motion models conditioned on these expectable events. Together with a mapper that constructs a semantic spatial map on-the-fly during navigation, we formulate an end-to-end differentiable Bayes filter and train it to identify the goal by predicting the most likely trajectory through the map according to the instructions. The resulting navigation policy constitutes a new approach to instruction following that explicitly models a probability distribution over states, encoding strong geometric and algorithmic priors while enabling greater explainability. Our experiments show that our approach outperforms strong baselines when predicting the goal location in VLN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02022](http://arxiv.org/abs/1907.02022)

##### PDF
[http://arxiv.org/pdf/1907.02022](http://arxiv.org/pdf/1907.02022)

