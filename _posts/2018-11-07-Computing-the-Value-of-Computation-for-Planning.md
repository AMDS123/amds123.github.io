---
layout: post
title: "Computing the Value of Computation for Planning"
date: 2018-11-07 17:39:24
categories: arXiv_AI
tags: arXiv_AI
author: Can Eren Sezener
mathjax: true
---

* content
{:toc}

##### Abstract
An intelligent agent performs actions in order to achieve its goals. Such actions can either be externally directed, such as opening a door, or internally directed, such as writing data to a memory location or strengthening a synaptic connection. Some internal actions, to which we refer as computations, potentially help the agent choose better actions. Considering that (external) actions and computations might draw upon the same resources, such as time and energy, deciding when to act or compute, as well as what to compute, are detrimental to the performance of an agent. 
 In an environment that provides rewards depending on an agent's behavior, an action's value is typically defined as the sum of expected long-term rewards succeeding the action (itself a complex quantity that depends on what the agent goes on to do after the action in question). However, defining the value of a computation is not as straightforward, as computations are only valuable in a higher order way, through the alteration of actions. 
 This thesis offers a principled way of computing the value of a computation in a planning setting formalized as a Markov decision process. We present two different definitions of computation values: static and dynamic. They address two extreme cases of the computation budget: affording calculation of zero or infinitely many steps in the future. We show that these values have desirable properties, such as temporal consistency and asymptotic convergence. 
 Furthermore, we propose methods for efficiently computing and approximating the static and dynamic computation values. We describe a sense in which the policies that greedily maximize these values can be optimal. We utilize these principles to construct Monte Carlo tree search algorithms that outperform most of the state-of-the-art in terms of finding higher quality actions given the same simulation resources.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03035](http://arxiv.org/abs/1811.03035)

##### PDF
[http://arxiv.org/pdf/1811.03035](http://arxiv.org/pdf/1811.03035)

