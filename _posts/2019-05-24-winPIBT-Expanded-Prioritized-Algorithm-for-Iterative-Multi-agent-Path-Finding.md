---
layout: post
title: "winPIBT: Expanded Prioritized Algorithm for Iterative Multi-agent Path Finding"
date: 2019-05-24 11:12:25
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Keisuke Okumura, Yasumasa Tamura, Xavier D&#xe9;fago
mathjax: true
---

* content
{:toc}

##### Abstract
Providing agents with efficient paths so as not to collide with each other are called the Multi-agent Path Finding (MAPF) problem. Numerous solvers have been developed so far since MAPF is critical for practical applications such as automated warehouses. Priority Inheritance with Backtracking (PIBT) is an instance of decoupled approach which solves MAPF iteratively by flexible prioritized planning. PIBT plans the paths of all agents one step at a time, i.e., the time window size is just one, and this locality causes inefficient path planning in some cases. In this work, we propose a generalized algorithm of PIBT with respect to the time window, called Windowed Priority Inheritance with Backtracking (winPIBT). winPIBT expands PIBT by enabling retroactive priority inheritance and backtracking. We prove that, similar to PIBT, all agents reach their own destinations in finite time as long as the environment is a graph such that all pairs of adjacent nodes belong to a simple cycle of length 3 or more (e.g., biconnected). We evaluate winPIBT through simulation in various environments while changing the window size. Our results confirm that winPIBT mitigates livelock situations occurring in PIBT, and plans more efficient paths depending on the window size.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10149](http://arxiv.org/abs/1905.10149)

##### PDF
[http://arxiv.org/pdf/1905.10149](http://arxiv.org/pdf/1905.10149)

