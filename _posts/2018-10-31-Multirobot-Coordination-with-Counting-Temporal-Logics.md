---
layout: post
title: "Multirobot Coordination with Counting Temporal Logics"
date: 2018-10-31 03:08:13
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Yunus Emre Sahin, Petter Nilsson, Necmiye Ozay
mathjax: true
---

* content
{:toc}

##### Abstract
In many multirobot applications, planning trajectories in a way to guarantee that the collective behavior of the robots satisfies a certain high-level specification is crucial. Motivated by this problem, we introduce counting temporal logics---formal languages that enable concise expression of multirobot task specifications over possibly infinite horizons. We first introduce a general logic called counting linear temporal logic plus (cLTL+), and propose an optimization-based method that generates individual trajectories such that satisfaction of a given cLTL+ formula is guaranteed when these trajectories are synchronously executed. We then introduce a fragment of cLTL+, called counting linear temporal logic (cLTL), and show that a solution to planning problem with cLTL constraints can be obtained more efficiently if all robots have identical dynamics. In the second part of the paper, we relax the synchrony assumption and discuss how to generate trajectories that can be asynchronously executed, while preserving the satisfaction of the desired cLTL+ specification. In particular, we show that when the asynchrony between robots is bounded, the method presented in this paper can be modified to generate robust trajectories. We demonstrate these ideas with an experiment and provide numerical results that showcase the scalability of the method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.13087](http://arxiv.org/abs/1810.13087)

##### PDF
[http://arxiv.org/pdf/1810.13087](http://arxiv.org/pdf/1810.13087)

