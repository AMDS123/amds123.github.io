---
layout: post
title: "Transition-based versus State-based Reward Functions for MDPs with Value-at-Risk"
date: 2018-11-29 22:50:03
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Shuai Ma, Jia Yuan Yu
mathjax: true
---

* content
{:toc}

##### Abstract
In reinforcement learning, the reward function on current state and action is widely used. When the objective is about the expectation of the (discounted) total reward only, it works perfectly. However, if the objective involves the total reward distribution, the result will be wrong. This paper studies Value-at-Risk (VaR) problems in short- and long-horizon Markov decision processes (MDPs) with two reward functions, which share the same expectations. Firstly we show that with VaR objective, when the real reward function is transition-based (with respect to action and both current and next states), the simplified (state-based, with respect to action and current state only) reward function will change the VaR. Secondly, for long-horizon MDPs, we estimate the VaR function with the aid of spectral theory and the central limit theorem. Thirdly, since the estimation method is for a Markov reward process with the reward function on current state only, we present a transformation algorithm for the Markov reward process with the reward function on current and next states, in order to estimate the VaR function with an intact total reward distribution.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1612.02088](http://arxiv.org/abs/1612.02088)

##### PDF
[http://arxiv.org/pdf/1612.02088](http://arxiv.org/pdf/1612.02088)

