---
layout: post
title: "Pattern-Based Approach to the Workflow Satisfiability Problem with User-Independent Constraints"
date: 2019-02-01 15:33:12
categories: arXiv_AI
tags: arXiv_AI
author: Daniel Karapetyan, Andrew J. Parkes, Gregory Gutin, Andrei Gagarin
mathjax: true
---

* content
{:toc}

##### Abstract
The fixed parameter tractable (FPT) approach is a powerful tool in tackling computationally hard problems. In this paper, we link FPT results to classic artificial intelligence (AI) techniques to show how they complement each other. Specifically, we consider the workflow satisfiability problem (WSP) which asks whether there exists an assignment of authorised users to the steps in a workflow specification, subject to certain constraints on the assignment. It was shown by Cohen et al. (JAIR 2014) that WSP restricted to the class of user-independent constraints (UI), covering many practical cases, admits FPT algorithms, i.e. can be solved in time exponential only in the number of steps $k$ and polynomial in the number of users $n$. Since usually $k \ll n$ in WSP, such FPT algorithms are of great practical interest. 
 We present a new interpretation of the FPT nature of the WSP with UI constraints giving a decomposition of the problem into two levels. Exploiting this two-level split, we develop a new FPT algorithm that is by many orders of magnitude faster than the previous state-of-the-art WSP algorithm and also has only polynomial-space complexity. We also introduce new pseudo-Boolean (PB) and Constraint Satisfaction (CSP) formulations of the WSP with UI constraints which efficiently exploit this new decomposition of the problem and raise the novel issue of how to use general-purpose solvers to tackle FPT problems in a fashion that meets FPT efficiency expectations. In our computational study, we investigate, for the first time, the phase transition (PT) properties of the WSP, under a model for generation of random instances. We show how PT studies can be extended, in a novel fashion, to support empirical evaluation of scaling of FPT algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1604.05636](http://arxiv.org/abs/1604.05636)

##### PDF
[http://arxiv.org/pdf/1604.05636](http://arxiv.org/pdf/1604.05636)

