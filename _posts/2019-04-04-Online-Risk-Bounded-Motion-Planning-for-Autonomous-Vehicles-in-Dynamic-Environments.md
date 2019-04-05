---
layout: post
title: "Online Risk-Bounded Motion Planning for Autonomous Vehicles in Dynamic Environments"
date: 2019-04-04 04:19:38
categories: arXiv_AI
tags: arXiv_AI Recognition
author: Xin Huang, Sungkweon Hong, Andreas Hofmann, Brian C. Williams
mathjax: true
---

* content
{:toc}

##### Abstract
A crucial challenge to efficient and robust motion planning for autonomous vehicles is understanding the intentions of the surrounding agents. Ignoring the intentions of the other agents in dynamic environments can lead to risky or over-conservative plans. In this work, we model the motion planning problem as a partially observable Markov decision process (POMDP) and propose an online system that combines an intent recognition algorithm and a POMDP solver to generate risk-bounded plans for the ego vehicle navigating with a number of dynamic agent vehicles. The intent recognition algorithm predicts the probabilistic hybrid motion states of each agent vehicle over a finite horizon using Bayesian filtering and a library of pre-learned maneuver motion models. We update the POMDP model with the intent recognition results in real time and solve it using a heuristic search algorithm which produces policies with upper-bound guarantees on the probability of near colliding with other dynamic agents. We demonstrate that our system is able to generate better motion plans in terms of efficiency and safety in a number of challenging environments including unprotected intersection left turns and lane changes as compared to the baseline methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02341](http://arxiv.org/abs/1904.02341)

##### PDF
[http://arxiv.org/pdf/1904.02341](http://arxiv.org/pdf/1904.02341)

