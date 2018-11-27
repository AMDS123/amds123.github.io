---
layout: post
title: "RADMPC: A Fast Decentralized Approach for Chance-Constrained Multi-Vehicle Path-Planning"
date: 2018-11-25 00:43:32
categories: arXiv_RO
tags: arXiv_RO
author: Aaron Huang, Benjamin J. Ayton, Brian C. Williams
mathjax: true
---

* content
{:toc}

##### Abstract
Robust multi-vehicle path-planning is important for ensuring the safety of multi-vehicle systems in applications like transportation, search and rescue, and robotic exploration. Chance-constrained methods like Iterative Risk Allocation (IRA)\cite{IRA} have been developed for situations where environmental disturbances are unbounded. However, chance-constrained methods for the multi-vehicle case generally use centralized strategies where the vehicle set is planned with couplings between all vehicle pairs. This approach is intractable as fleet size increases because computation time is exponential with respect to the number of vehicles being planned over due to a polynomial increase in coupling constraints between vehicle pairs. We present a faster approach for chance-constrained multi-vehicle path-planning that relies upon a decentralized path-planning method called Risk-Aware Decentralized Model Predictive Control (RADMPC) to rapidly approximate a centralized IRA approach. The RADMPC approximation is evaluated for vehicle interactions to determine the vehicle sets that should be planned in a coupled manner. Applying IRA to the smaller vehicle sets determined from the RADMPC approximation rapidly plans safe paths for the entire fleet. A Monte Carlo simulation analysis demonstrates the correctness of our approach and a significant improvement in computation time compared to a centralized IRA approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09914](http://arxiv.org/abs/1811.09914)

##### PDF
[http://arxiv.org/pdf/1811.09914](http://arxiv.org/pdf/1811.09914)

