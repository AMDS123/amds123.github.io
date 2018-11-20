---
layout: post
title: "Learning Features and Abstract Actions for Computing Generalized Plans"
date: 2018-11-17 22:05:04
categories: arXiv_AI
tags: arXiv_AI
author: Blai Bonet, Guillem Franc&#xe8;s, Hector Geffner
mathjax: true
---

* content
{:toc}

##### Abstract
Generalized planning is concerned with the computation of plans that solve not one but multiple instances of a planning domain. Recently, it has been shown that generalized plans can be expressed as mappings of feature values into actions, and that they can often be computed with fully observable non-deterministic (FOND) planners. The actions in such plans, however, are not the actions in the instances themselves, which are not necessarily common to other instances, but abstract actions that are defined on a set of common features. The formulation assumes that the features and the abstract actions are given. In this work, we address this limitation by showing how to learn them automatically. The resulting account of generalized planning combines learning and planning in a novel way: a learner, based on a Max SAT formulation, yields the features and abstract actions from sampled state transitions, and a FOND planner uses this information, suitably transformed, to produce the general plans. Correctness guarantees are given and experimental results on several domains are reported.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07231](http://arxiv.org/abs/1811.07231)

##### PDF
[http://arxiv.org/pdf/1811.07231](http://arxiv.org/pdf/1811.07231)

