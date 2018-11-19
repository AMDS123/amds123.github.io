---
layout: post
title: "Expanding Motor Skills through Relay Neural Networks"
date: 2018-11-15 23:13:35
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Visak C.V.Kumar, Sehoon Ha, C. Karen Liu
mathjax: true
---

* content
{:toc}

##### Abstract
While the recent advances in deep reinforcement learning have achieved impressive results in learning motor skills, many of the trained policies are only capable within a limited set of initial states. We propose a technique to break down a complex robotic task to simpler subtasks and train them sequentially such that the robot can expand its existing skill set gradually. Our key idea is to build a tree of local control policies represented by neural networks, which we refer as Relay Neural Networks. Starting from the root policy that attempts to achieve the task from a small set of initial states, each subsequent policy expands the set of successful initial states by driving the new states to existing "good" states. Our algorithm utilizes the value function of the policy to determine whether a state is "good" under each policy. We take advantage of many existing policy search algorithms that learn the value function simultaneously with the policy, such as those that use actor-critic representations or those that use the advantage function to reduce variance. We demonstrate that the relay networks can solve complex continuous control problems for underactuated dynamic systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1709.07932](http://arxiv.org/abs/1709.07932)

##### PDF
[http://arxiv.org/pdf/1709.07932](http://arxiv.org/pdf/1709.07932)

