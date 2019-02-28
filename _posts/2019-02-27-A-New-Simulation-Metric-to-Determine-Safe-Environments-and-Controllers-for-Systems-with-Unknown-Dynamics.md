---
layout: post
title: "A New Simulation Metric to Determine Safe Environments and Controllers for Systems with Unknown Dynamics"
date: 2019-02-27 03:30:01
categories: arXiv_RO
tags: arXiv_RO Relation
author: Shromona Ghosh, Somil Bansal, Alberto Sangiovanni-Vincentelli, Sanjit A. Seshia, Claire J. Tomlin
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of extracting safe environments and controllers for reach-avoid objectives for systems with known state and control spaces, but unknown dynamics. In a given environment, a common approach is to synthesize a controller from an abstraction or a model of the system (potentially learned from data). However, in many situations, the relationship between the dynamics of the model and the \textit{actual system} is not known; and hence it is difficult to provide safety guarantees for the system. In such cases, the Standard Simulation Metric (SSM), defined as the worst-case norm distance between the model and the system output trajectories, can be used to modify a reach-avoid specification for the system into a more stringent specification for the abstraction. Nevertheless, the obtained distance, and hence the modified specification, can be quite conservative. This limits the set of environments for which a safe controller can be obtained. We propose SPEC, a specification-centric simulation metric, which overcomes these limitations by computing the distance using only the trajectories that violate the specification for the system. We show that modifying a reach-avoid specification with SPEC allows us to synthesize a safe controller for a larger set of environments compared to SSM. We also propose a probabilistic method to compute SPEC for a general class of systems. Case studies using simulators for quadrotors and autonomous cars illustrate the advantages of the proposed metric for determining safe environment sets and controllers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10320](http://arxiv.org/abs/1902.10320)

##### PDF
[http://arxiv.org/pdf/1902.10320](http://arxiv.org/pdf/1902.10320)

