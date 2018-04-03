---
layout: post
title: "Learning to Reason with HOL4 tactics"
date: 2018-04-02 15:41:09
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Thibault Gauthier, Cezary Kaliszyk, Josef Urban
mathjax: true
---

* content
{:toc}

##### Abstract
Techniques combining machine learning with translation to automated reasoning have recently become an important component of formal proof assistants. Such "hammer" tech- niques complement traditional proof assistant automation as implemented by tactics and decision procedures. In this paper we present a unified proof assistant automation approach which attempts to automate the selection of appropriate tactics and tactic-sequences com- bined with an optimized small-scale hammering approach. We implement the technique as a tactic-level automation for HOL4: TacticToe. It implements a modified A*-algorithm directly in HOL4 that explores different tactic-level proof paths, guiding their selection by learning from a large number of previous tactic-level proofs. Unlike the existing hammer methods, TacticToe avoids translation to FOL, working directly on the HOL level. By combining tactic prediction and premise selection, TacticToe is able to re-prove 39 percent of 7902 HOL4 theorems in 5 seconds whereas the best single HOL(y)Hammer strategy solves 32 percent in the same amount of time.

##### Abstract (translated by Google)
将机器学习与翻译结合起来进行自动推理的技术最近已成为正式证明助手的重要组成部分。这种“锤子”技术与传统的证明助理自动化相辅相成，如策略和决策程序所实施的那样。在本文中，我们提出了一种统一的证明助理自动化方法，试图自动选择合适的策略和战术序列，并结合优化的小型锤击方法。我们将该技术实施为HOL4：TacticToe的战术级自动化。它直接在HOL4中实现了一个修改的A *算法，该算法探索了不同的策略级证明路径，通过从大量以前的策略级证明中学习来指导它们的选择。与现有的锤击方法不同，TacticToe避免了直接在HOL级别上转换为FOL。通过结合战术预测和前提选择，TacticToe能够在5秒内重新验证7902个HOL4定理中的39％，而最佳单个HOL（y）锤策略在相同的时间内解决32％。

##### URL
[http://arxiv.org/abs/1804.00595](http://arxiv.org/abs/1804.00595)

##### PDF
[http://arxiv.org/pdf/1804.00595](http://arxiv.org/pdf/1804.00595)

