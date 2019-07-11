---
layout: post
title: "Robust Humanoid Locomotion Using Trajectory Optimization and Sample-Efficient Learning"
date: 2019-07-10 11:10:56
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Mohammad Hasan Yeganegi, Majid Khadiv, S. Ali A. Moosavian, Jia-Jie Zhu, Andrea Del Prete, Ludovic Righetti
mathjax: true
---

* content
{:toc}

##### Abstract
Trajectory optimization (TO) is one of the most powerful tools for generating feasible motions for humanoid robots. However, including uncertainties and stochasticity in the TO problem to generate robust motions can easily lead to intractable problems. Furthermore, since the models used in TO have always some level of abstraction, it can be hard to find a realistic set of uncertainties in the model space. In this paper we leverage a sample-efficient learning technique (Bayesian optimization) to robustify TO for humanoid locomotion. The main idea is to use data from full-body simulations to make the TO stage robust by tuning the cost weights. To this end, we split the TO problem into two phases. The first phase solves a convex optimization problem for generating center of mass (CoM) trajectories based on simplified linear dynamics. The second stage employs iterative Linear-Quadratic Gaussian (iLQG) as a whole-body controller to generate full body control inputs. Then we use Bayesian optimization to find the cost weights to use in the first stage that yields robust performance in the simulation/experiment, in the presence of different disturbance/uncertainties. The results show that the proposed approach is able to generate robust motions for different sets of disturbances and uncertainties.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04616](http://arxiv.org/abs/1907.04616)

##### PDF
[http://arxiv.org/pdf/1907.04616](http://arxiv.org/pdf/1907.04616)

