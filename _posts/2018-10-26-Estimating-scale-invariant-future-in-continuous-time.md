---
layout: post
title: "Estimating scale-invariant future in continuous time"
date: 2018-10-26 23:46:21
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: Zoran Tiganj, Samuel J. Gershman, Per B. Sederberg, Marc W. Howard
mathjax: true
---

* content
{:toc}

##### Abstract
Natural learners must compute an estimate of future outcomes that follow from a stimulus in continuous time. Widely used reinforcement learning algorithms discretize continuous time and estimate either transition functions from one step to the next (model-based algorithms) or a scalar value of exponentially-discounted future reward using the Bellman equation (model-free algorithms). An important drawback of model-based algorithms is that computational cost grows linearly with the amount of time to be simulated. On the other hand, an important drawback of model-free algorithms is the need to select a time-scale required for exponential discounting. We present a computational mechanism, developed based on work in psychology and neuroscience, for computing a scale-invariant timeline of future outcomes. This mechanism efficiently computes an estimate of inputs as a function of future time on a logarithmically-compressed scale, and can be used to generate a scale-invariant power-law-discounted estimate of expected future reward. The representation of future time retains information about what will happen when. The entire timeline can be constructed in a single parallel operation which generates concrete behavioral and neural predictions. This computational mechanism could be incorporated into future reinforcement learning algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.06426](http://arxiv.org/abs/1802.06426)

##### PDF
[http://arxiv.org/pdf/1802.06426](http://arxiv.org/pdf/1802.06426)

