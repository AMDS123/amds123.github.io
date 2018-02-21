---
layout: post
title: "Using Automatic Generation of Relaxation Constraints to Improve the Preimage Attack on 39-step MD4"
date: 2018-02-20 02:47:41
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Gribanova Irina, Semenov Alexander
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we construct preimage attack on the truncated variant of the MD4 hash function. Specifically, we study the MD4-39 function defined by the first 39 steps of the MD4 algorithm. We suggest a new attack on MD4-39, which develops the ideas proposed by H. Dobbertin in 1998. Namely, the special relaxation constraints are introduced in order to simplify the equations corresponding to the problem of finding a preimage for an arbitrary MD4-39 hash value. The equations supplemented with the relaxation constraints are then reduced to the Boolean Satisfiability Problem (SAT) and solved using the state-of-the-art SAT solvers. We show that the effectiveness of a set of relaxation constraints can be evaluated using the black-box function of a special kind. Thus, we suggest automatic method of relaxation constraints generation by applying the black-box optimization to this function. The proposed method made it possible to find new relaxation constraints that contribute to a SAT-based preimage attack on MD4-39 which significantly outperforms the competition.

##### Abstract (translated by Google)
在本文中，我们构造了对MD4哈希函数的截断变体的前像攻击。具体而言，我们研究了MD4算法的前39个步骤定义的MD4-39函数。我们建议对MD4-39进行一次新的攻击，它发展了H. Dobbertin在1998年提出的想法。也就是说，引入了特殊的松弛约束，以便简化与寻找任意MD4-39原像相对应的方程哈希值。然后将补充了松弛约束的方程简化为布尔可满足性问题（SAT），并使用最先进的SAT求解器求解。我们表明，可以使用特殊类型的黑盒函数来评估一组放松约束条件的有效性。因此，我们建议通过对这个函数应用黑盒子优化来自动产生松弛约束。所提出的方法使得有可能找到新的放松约束条件，这些约束条件导致基于SAT的原像攻击显着优于竞争对手的MD4-39。

##### URL
[http://arxiv.org/abs/1802.06940](http://arxiv.org/abs/1802.06940)

##### PDF
[http://arxiv.org/pdf/1802.06940](http://arxiv.org/pdf/1802.06940)

