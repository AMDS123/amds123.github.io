---
layout: post
title: "Randomised Bayesian Least-Squares Policy Iteration"
date: 2019-04-06 21:50:24
categories: arXiv_AI
tags: arXiv_AI
author: Nikolaos Tziortziotis, Christos Dimitrakakis, Michalis Vazirgiannis
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Bayesian least-squares policy iteration (BLSPI), an off-policy, model-free, policy iteration algorithm that uses the Bayesian least-squares temporal-difference (BLSTD) learning algorithm to evaluate policies. An online variant of BLSPI has been also proposed, called randomised BLSPI (RBLSPI), that improves its policy based on an incomplete policy evaluation step. In online setting, the exploration-exploitation dilemma should be addressed as we try to discover the optimal policy by using samples collected by ourselves. RBLSPI exploits the advantage of BLSTD to quantify our uncertainty about the value function. Inspired by Thompson sampling, RBLSPI first samples a value function from a posterior distribution over value functions, and then selects actions based on the sampled value function. The effectiveness and the exploration abilities of RBLSPI are demonstrated experimentally in several environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03535](http://arxiv.org/abs/1904.03535)

##### PDF
[http://arxiv.org/pdf/1904.03535](http://arxiv.org/pdf/1904.03535)

