---
layout: post
title: "Learning to Prove with Tactics"
date: 2018-04-02 15:43:17
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Thibault Gauthier, Cezary Kaliszyk, Josef Urban, Ramana Kumar, Michael Norrish
mathjax: true
---

* content
{:toc}

##### Abstract
We implement a automated tactical prover TacticToe on top of the HOL4 interactive theorem prover. TacticToe learns from human proofs which mathematical technique is suitable in each proof situation. This knowledge is then used in a Monte Carlo tree search algorithm to explore promising tactic-level proof paths. On a single CPU, with a time limit of 60 seconds, TacticToe proves 66.4 percent of the 7164 theorems in HOL4's standard library, whereas E prover with auto-schedule solves 34.5 percent. The success rate rises to 69.0 percent by combining the results of TacticToe and E prover.

##### Abstract (translated by Google)
我们在HOL4交互式定理证明器之上实施了自动化战术证明器TacticToe。 TacticToe从人类的证明中学习哪种数学技术适用于每种证明情况。然后将这些知识用于蒙特卡罗树搜索算法中，以探索有前途的策略级证明路径。在单个CPU上，时间限制为60秒，TacticToe证明了HOL4标准库中7164定理的66.4％，而具有自动时间表的E证明器解决了34.5％的问题。结合TacticToe和E证明者的结果，成功率提高到69.0％。

##### URL
[http://arxiv.org/abs/1804.00596](http://arxiv.org/abs/1804.00596)

##### PDF
[http://arxiv.org/pdf/1804.00596](http://arxiv.org/pdf/1804.00596)

