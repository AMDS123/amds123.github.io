---
layout: post
title: "Massively Parallel Benders Decomposition for Correlation Clustering"
date: 2019-02-15 01:50:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization Relation
author: Margret Keuper, Maneesh Singh, Julian Yarkony
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of graph partitioning for image segmentation using correlation clustering (CC), which we treat as an integer linear program (ILP). We reformulate optimization in the ILP so as to admit efficient optimization via Benders decomposition, a classic technique from operations research. Our Benders decomposition formulation has many subproblems, each associated with a node in the CC instance's graph, which are solved in parallel. Each Benders subproblem enforces the cycle inequalities corresponding to the negative weight edges attached to its corresponding node in the CC instance. We generate Magnanti-Wong Benders rows in addition to standard Benders rows, to accelerate optimization. Our Benders decomposition approach provides a promising new avenue to accelerate optimization for CC, and allows for massive parallelization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05659](http://arxiv.org/abs/1902.05659)

##### PDF
[http://arxiv.org/pdf/1902.05659](http://arxiv.org/pdf/1902.05659)

