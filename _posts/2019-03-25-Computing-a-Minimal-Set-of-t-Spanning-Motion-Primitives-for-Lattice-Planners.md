---
layout: post
title: "Computing a Minimal Set of t-Spanning Motion Primitives for Lattice Planners"
date: 2019-03-25 17:29:46
categories: arXiv_RO
tags: arXiv_RO
author: Alexander Botros, Stephen L. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we consider the problem of computing an optimal set of motion primitives for a lattice planner. The objective we consider is to compute a minimal set of motion primitives that t-span a configuration space lattice. A set of motion primitives t-span a lattice if, given a real number t greater or equal to one, any configuration in the lattice can be reached via a sequence of motion primitives whose cost is no more than t times the cost of the optimal path to that configuration. Determining the smallest set of t-spanning motion primitives allows for quick traversal of a state lattice in the context of robotic motion planning, while maintaining a t-factor adherence to the theoretically optimal path. While several heuristics exist to determine a t-spanning set of motion primitives, these are presented without guarantees on the size of the set relative to optimal. This paper provides a proof that the minimal t-spanning control set problem for a lattice defined over an arbitrary robot configuration space is NP-complete, and presents a compact mixed integer linear programming formulation to compute an optimal t-spanner. We show that solutions obtained by the mixed integer linear program have significantly fewer motion primitives than state of the art heuristic algorithms, and out perform a set of standard primitives used in robotic path planning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10483](http://arxiv.org/abs/1903.10483)

##### PDF
[http://arxiv.org/pdf/1903.10483](http://arxiv.org/pdf/1903.10483)

