---
layout: post
title: "Leveraging Experience in Lazy Search"
date: 2019-07-16 20:03:57
categories: arXiv_RO
tags: arXiv_RO
author: Mohak Bhardwaj, Sanjiban Choudhury, Byron Boots, Siddhartha Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
Lazy graph search algorithms are efficient at solving motion planning problems where edge evaluation is the computational bottleneck. These algorithms work by lazily computing the shortest potentially feasible path, evaluating edges along that path, and repeating until a feasible path is found. The order in which edges are selected is critical to minimizing the total number of edge evaluations: a good edge selector chooses edges that are not only likely to be invalid, but also eliminates future paths from consideration. We wish to learn such a selector by leveraging prior experience. We formulate this problem as a Markov Decision Process (MDP) on the state of the search problem. While solving this large MDP is generally intractable, we show that we can compute oracular selectors that can solve the MDP during training. With access to such oracles, we use imitation learning to find effective policies. If new search problems are sufficiently similar to problems solved during training, the learned policy will choose a good edge evaluation ordering and solve the motion planning problem quickly. We evaluate our algorithms on a wide range of 2D and 7D problems and show that the learned selector outperforms baseline commonly used heuristics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07238](http://arxiv.org/abs/1907.07238)

##### PDF
[http://arxiv.org/pdf/1907.07238](http://arxiv.org/pdf/1907.07238)

