---
layout: post
title: "Learning Stabilizable Nonlinear Dynamics with Contraction-Based Regularization"
date: 2019-07-29 21:14:34
categories: arXiv_RO
tags: arXiv_RO Regularization Tracking Optimization
author: Sumeet Singh, Spencer M. Richards, Vikas Sindhwani, Jean-Jacques E. Slotine, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel framework for learning stabilizable nonlinear dynamical systems for continuous control tasks in robotics. The key contribution is a control-theoretic regularizer for dynamics fitting rooted in the notion of stabilizability, a constraint which guarantees the existence of robust tracking controllers for arbitrary open-loop trajectories generated with the learned system. Leveraging tools from contraction theory and statistical learning in Reproducing Kernel Hilbert Spaces, we formulate stabilizable dynamics learning as a functional optimization with convex objective and bi-convex functional constraints. Under a mild structural assumption and relaxation of the functional constraints to sampling-based constraints, we derive the optimal solution with a modified Representer theorem. Finally, we utilize random matrix feature approximations to reduce the dimensionality of the search parameters and formulate an iterative convex optimization algorithm that jointly fits the dynamics functions and searches for a certificate of stabilizability. We validate the proposed algorithm in simulation for a planar quadrotor, and on a quadrotor hardware testbed emulating planar dynamics. We verify, both in simulation and on hardware, significantly improved trajectory generation and tracking performance with the control-theoretic regularized model over models learned using traditional regression techniques, especially when learning from small supervised datasets. The results support the conjecture that the use of stabilizability constraints as a form of regularization can help prune the hypothesis space in a manner that is tailored to the downstream task of trajectory generation and feedback control, resulting in models that are not only dramatically better conditioned, but also data efficient.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13122](http://arxiv.org/abs/1907.13122)

##### PDF
[http://arxiv.org/pdf/1907.13122](http://arxiv.org/pdf/1907.13122)

