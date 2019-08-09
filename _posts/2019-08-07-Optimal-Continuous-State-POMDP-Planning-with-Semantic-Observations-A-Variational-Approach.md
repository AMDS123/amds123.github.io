---
layout: post
title: "Optimal Continuous State POMDP Planning with Semantic Observations: A Variational Approach"
date: 2019-08-07 22:03:41
categories: arXiv_AI
tags: arXiv_AI Relation
author: Luke Burks, Ian Loefgren, Nisar Ahmed
mathjax: true
---

* content
{:toc}

##### Abstract
This work develops novel strategies for optimal planning with semantic observations using continuous state partially observable markov decision processes (CPOMDPs). Two major innovations are presented in relation to Gaussian mixture (GM) CPOMDP policy approximation methods. While existing methods have many desirable theoretical properties, they are unable to efficiently represent and reason over hybrid continuous-discrete probabilistic models. The first major innovation is the derivation of closed-form variational Bayes GM approximations of Point-Based Value Iteration Bellman policy backups, using softmax models of continuous-discrete semantic observation probabilities. A key benefit of this approach is that dynamic decision-making tasks can be performed with complex non-Gaussian uncertainties, while also exploiting continuous dynamic state space models (thus avoiding cumbersome and costly discretization). The second major innovation is a new clustering-based technique for mixture condensation that scales well to very large GM policy functions and belief functions. Simulation results for a target search and interception task with semantic observations show that the GM policies resulting from these innovations are more effective than those produced by other state of the art policy approximations, but require significantly less modeling overhead and online runtime cost. Additional results show the robustness of this approach to model errors and scaling to higher dimensions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.08229](http://arxiv.org/abs/1807.08229)

##### PDF
[http://arxiv.org/pdf/1807.08229](http://arxiv.org/pdf/1807.08229)

