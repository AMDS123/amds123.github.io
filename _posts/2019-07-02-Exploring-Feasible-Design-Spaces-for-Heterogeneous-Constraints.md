---
layout: post
title: "Exploring Feasible Design Spaces for Heterogeneous Constraints"
date: 2019-07-02 01:11:49
categories: arXiv_RO
tags: arXiv_RO GAN Optimization Classification
author: Amir M. Mirzendehdel, Morad Behandish, Saigopal Nelaturi
mathjax: true
---

* content
{:toc}

##### Abstract
We demonstrate an approach of exploring design spaces to simultaneously satisfy kinematics- and physics-based requirements. We present a classification of constraints and solvers to enable postponing optimization as far down the design workflow as possible. The solvers are organized into two broad classes of design space 'pruning' and 'exploration' by considering the types of constraints they can satisfy. We show that pointwise constraints define feasible design subspaces that can be represented and computed as first-class entities by their maximal feasible elements. The design space is pruned upfront by intersecting maximal elements, without premature optimization. To solve for other constraints, we apply topology optimization (TO), starting from the pruned feasible space. The optimization is steered by a topological sensitivity field (TSF) that measures the global changes in violation of constraints with respect to local topological punctures. The TSF for global objective functions is augmented with TSF for global constraints, and penalized/filtered to incorporate local constraints, including set constraints converted to differentiable (in)equality constraints. We demonstrate application of the proposed workflow to nontrivial examples in design and manufacturing. Among other examples, we show how to explore pruned design spaces via TO to simultaneously satisfy physics-based constraints (e.g., minimize compliance and mass) as well as kinematics-based constraints (e.g., maximize accessibility for machining).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01117](http://arxiv.org/abs/1907.01117)

##### PDF
[http://arxiv.org/pdf/1907.01117](http://arxiv.org/pdf/1907.01117)

