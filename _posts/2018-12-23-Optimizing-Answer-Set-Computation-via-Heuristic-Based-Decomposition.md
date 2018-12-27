---
layout: post
title: "Optimizing Answer Set Computation via Heuristic-Based Decomposition"
date: 2018-12-23 14:35:58
categories: arXiv_AI
tags: arXiv_AI
author: Francesco Calimeri, Simona Perri, Jessica Zangari
mathjax: true
---

* content
{:toc}

##### Abstract
Answer Set Programming (ASP) is a purely declarative formalism developed in the field of logic programming and nonmonotonic reasoning: computational problems are encoded by logic programs whose answer sets, corresponding to solutions, are computed by an ASP system. Different, semantically equivalent, programs can be defined for the same problem; however, performance of systems evaluating them might significantly vary. We propose an approach for automatically transforming an input logic program into an equivalent one that can be evaluated more efficiently. One can make use of existing tree-decomposition techniques for rewriting selected rules into a set of multiple ones; the idea is to guide and adaptively apply them on the basis of proper new heuristics, to obtain a smart rewriting algorithm to be integrated into an ASP system. The method is rather general: it can be adapted to any system and implement different preference policies. Furthermore, we define a set of new heuristics tailored at optimizing grounding, one of the main phases of the ASP computation; we use them in order to implement the approach into the ASP system DLV, in particular into its grounding subsystem I-DLV, and carry out an extensive experimental activity for assessing the impact of the proposal. Under consideration in Theory and Practice of Logic Programming (TPLP).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09718](http://arxiv.org/abs/1812.09718)

##### PDF
[http://arxiv.org/pdf/1812.09718](http://arxiv.org/pdf/1812.09718)

