---
layout: post
title: "DAGs with NO TEARS: Continuous Optimization for Structure Learning"
date: 2018-11-03 01:29:29
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Xun Zheng, Bryon Aragam, Pradeep Ravikumar, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating the structure of directed acyclic graphs (DAGs, also known as Bayesian networks) is a challenging problem since the search space of DAGs is combinatorial and scales superexponentially with the number of nodes. Existing approaches rely on various local heuristics for enforcing the acyclicity constraint. In this paper, we introduce a fundamentally different strategy: We formulate the structure learning problem as a purely \emph{continuous} optimization problem over real matrices that avoids this combinatorial constraint entirely. This is achieved by a novel characterization of acyclicity that is not only smooth but also exact. The resulting problem can be efficiently solved by standard numerical algorithms, which also makes implementation effortless. The proposed method outperforms existing ones, without imposing any structural assumptions on the graph such as bounded treewidth or in-degree. Code implementing the proposed algorithm is open-source and publicly available at https://github.com/xunzheng/notears.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.01422](http://arxiv.org/abs/1803.01422)

##### PDF
[http://arxiv.org/pdf/1803.01422](http://arxiv.org/pdf/1803.01422)

