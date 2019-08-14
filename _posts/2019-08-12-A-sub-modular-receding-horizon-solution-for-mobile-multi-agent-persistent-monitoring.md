---
layout: post
title: "A sub-modular receding horizon solution for mobile multi-agent persistent monitoring"
date: 2019-08-12 22:24:19
categories: arXiv_RO
tags: arXiv_RO Optimization Detection
author: Navid Rezazadeh, Solmaz S. Kia
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of persistent monitoring of finite number of inter-connected geographical nodes for event detection via a group of heterogeneous mobile agents. We use Poisson process model to capture the probability of the events occurring at the geographical nodes. We then tie a utility function to the probability of detecting an event in each point of interest and use it in our policy design to incentivize the agents to visit the geographical nodes with higher probability of event occurrence. We show that the design of an optimal monitoring policy to maximize the utility of event detection over a mission horizon is an NP-hard problem. By showing that the reward function is a monotone increasing and submodular function, we then proceed to propose a suboptimal dispatch policy design with a known optimality gap. To reduce the time complexity of constructing the feasible search set and also to induce robustness to changes in event occurrence and other operational factors, we preform our suboptimal policy design in a receding horizon setting. Our next contribution is to add a new term to our optimization problem to compensate for the shortsightedness of the receding horizon approach. This added term provides a measure of importance for nodes beyond the receding horizon's sight, and is meant to give the policy design an intuition to steer the agents towards areas with higher importance on the global map. Finally, we discuss how our proposed algorithm can be implemented in a decentralized manner. We demonstrate our results through a simulation study.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04425](http://arxiv.org/abs/1908.04425)

##### PDF
[http://arxiv.org/pdf/1908.04425](http://arxiv.org/pdf/1908.04425)

