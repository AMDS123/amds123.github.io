---
layout: post
title: "A Non-Cooperative Game Approach to Autonomous Racing"
date: 2019-01-10 10:44:43
categories: arXiv_RO
tags: arXiv_RO
author: Alexander Liniger, John Lygeros
mathjax: true
---

* content
{:toc}

##### Abstract
We consider autonomous racing of two cars and present an approach to formulate racing decisions as a non-cooperative non-zero-sum game. We design three different games where the players aim to fulfill static track constraints as well as avoid collision with each other; the latter constraint depends on the combined actions of the two players. The difference between the games are the collision constraints and the payoff. In the first game collision avoidance is only considered by the follower, and each player maximizes their own progress towards the finish line. We show that, thanks to the sequential structure of this game, equilibria can be computed through an efficient sequential maximization approach. Further, we show these actions, if feasible, are also a Stackelberg and Nash equilibrium in pure strategies of our second game where both players consider the collision constraints. The payoff of our third game is designed to promote blocking, by additionally rewarding the cars for staying ahead at the end of the horizon. We show that this changes the Stackelberg equilibrium, but has a minor influence on the Nash equilibria. For online implementation, we propose to play the games in a moving horizon fashion, and discuss two methods for guaranteeing feasibility of the resulting coupled repeated games. Finally, we study the performance of the proposed approaches in simulation for a set-up that replicates the miniature race car tested at the Automatic Control Laboratory of ETH Zurich. The simulation study shows that the presented games can successfully model different racing behaviors and generate interesting racing situations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.03913](http://arxiv.org/abs/1712.03913)

##### PDF
[http://arxiv.org/pdf/1712.03913](http://arxiv.org/pdf/1712.03913)

