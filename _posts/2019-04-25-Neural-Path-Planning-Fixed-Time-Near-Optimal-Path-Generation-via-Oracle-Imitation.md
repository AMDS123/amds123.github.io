---
layout: post
title: "Neural Path Planning: Fixed Time, Near-Optimal Path Generation via Oracle Imitation"
date: 2019-04-25 00:05:24
categories: arXiv_AI
tags: arXiv_AI RNN
author: Mayur J. Bency, Ahmed H. Qureshi, Michael C. Yip
mathjax: true
---

* content
{:toc}

##### Abstract
Fast and efficient path generation is critical for robots operating in complex environments. This motion planning problem is often performed in a robot's actuation or configuration space, where popular pathfinding methods such as A*, RRT*, get exponentially more computationally expensive to execute as the dimensionality increases or the spaces become more cluttered and complex. On the other hand, if one were to save the entire set of paths connecting all pair of locations in the configuration space a priori, one would run out of memory very quickly. In this work, we introduce a novel way of producing fast and optimal motion plans for static environments by using a stepping neural network approach, called OracleNet. OracleNet uses Recurrent Neural Networks to determine end-to-end trajectories in an iterative manner that implicitly generates optimal motion plans with minimal loss in performance in a compact form. The algorithm is straightforward in implementation while consistently generating near-optimal paths in a single, iterative, end-to-end roll-out. In practice, OracleNet generally has fixed-time execution regardless of the configuration space complexity while outperforming popular pathfinding algorithms in complex environments and higher dimensions

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11102](http://arxiv.org/abs/1904.11102)

##### PDF
[http://arxiv.org/pdf/1904.11102](http://arxiv.org/pdf/1904.11102)

