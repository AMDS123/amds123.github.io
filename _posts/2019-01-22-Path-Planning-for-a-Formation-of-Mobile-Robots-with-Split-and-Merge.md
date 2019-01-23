---
layout: post
title: "Path Planning for a Formation of Mobile Robots with Split and Merge"
date: 2019-01-22 15:22:12
categories: arXiv_RO
tags: arXiv_RO
author: Estefan&#xed;a Pereyra, Gast&#xf3;n Aragu&#xe1;s, Miroslav Kulich
mathjax: true
---

* content
{:toc}

##### Abstract
A novel multi-robot path planning approach is presented in this paper. Based on the standard Dijkstra, the algorithm looks for the optimal paths for a formation of robots, taking into account the possibility of split and merge. The algorithm explores a graph representation of the environment, computing for each node the cost of moving a number of robots and their corresponding paths. In every node where the formation can split, all the new possible formation subdivisions are taken into account accordingly to their individual costs. In the same way, in every node where the formation can merge, the algorithm verifies whether the combination is possible and, if possible, computes the new cost. In order to manage split and merge situations, a set of constraints is applied. The proposed algorithm is thus deterministic, complete and finds an optimal solution from a source node to all other nodes in the graph. The presented solution is general enough to be incorporated into high-level tasks as well as it can benefit from state-of-the-art formation motion planning approaches, which can be used for evaluation of edges of an input graph. The presented experimental results demonstrate the ability of the method to find the optimal solution for a formation of robots in environments with varying complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07408](http://arxiv.org/abs/1901.07408)

##### PDF
[http://arxiv.org/pdf/1901.07408](http://arxiv.org/pdf/1901.07408)

