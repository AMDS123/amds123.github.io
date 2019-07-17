---
layout: post
title: "Efficient Autonomy Validation in Simulation with Adaptive Stress Testing"
date: 2019-07-16 00:12:09
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Detection Relation
author: Mark Koren, Mykel Kochenderfer
mathjax: true
---

* content
{:toc}

##### Abstract
During the development of autonomous systems such as driverless cars, it is important to characterize the scenarios that are most likely to result in failure. Adaptive Stress Testing (AST) provides a way to search for the most-likely failure scenario as a Markov decision process (MDP). Our previous work used a deep reinforcement learning (DRL) solver to identify likely failure scenarios. However, the solver's use of a feed-forward neural network with a discretized space of possible initial conditions poses two major problems. First, the system is not treated as a black box, in that it requires analyzing the internal state of the system, which leads to considerable implementation complexities. Second, in order to simulate realistic settings, a new instance of the solver needs to be run for each initial condition. Running a new solver for each initial condition not only significantly increases the computational complexity, but also disregards the underlying relationship between similar initial conditions. We provide a solution to both problems by employing a recurrent neural network that takes a set of initial conditions from a continuous space as input. This approach enables robust and efficient detection of failures because the solution generalizes across the entire space of initial conditions. By simulating an instance where an autonomous car drives while a pedestrian is crossing a road, we demonstrate the solver is now capable of finding solutions for problems that would have previously been intractable.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06795](http://arxiv.org/abs/1907.06795)

##### PDF
[http://arxiv.org/pdf/1907.06795](http://arxiv.org/pdf/1907.06795)

