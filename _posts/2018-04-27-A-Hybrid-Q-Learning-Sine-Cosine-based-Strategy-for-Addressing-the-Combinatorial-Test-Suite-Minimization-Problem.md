---
layout: post
title: "A Hybrid Q-Learning Sine-Cosine-based Strategy for Addressing the Combinatorial Test Suite Minimization Problem"
date: 2018-04-27 12:44:04
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Kamal Z. Zamli, Fakhrud Din, Bestoun S. Ahmed, Miroslav Bures
mathjax: true
---

* content
{:toc}

##### Abstract
The sine-cosine algorithm (SCA) is a new population-based meta-heuristic algorithm. In addition to exploiting sine and cosine functions to perform local and global searches (hence the name sine-cosine), the SCA introduces several random and adaptive parameters to facilitate the search process. Although it shows promising results, the search process of the SCA is vulnerable to local minima/maxima due to the adoption of a fixed switch probability and the bounded magnitude of the sine and cosine functions (from -1 to 1). In this paper, we propose a new hybrid Q-learning sine-cosine- based strategy, called the Q-learning sine-cosine algorithm (QLSCA). Within the QLSCA, we eliminate the switching probability. Instead, we rely on the Q-learning algorithm (based on the penalty and reward mechanism) to dynamically identify the best operation during runtime. Additionally, we integrate two new operations (L\'evy flight motion and crossover) into the QLSCA to facilitate jumping out of local minima/maxima and enhance the solution diversity. To assess its performance, we adopt the QLSCA for the combinatorial test suite minimization problem. Experimental results reveal that the QLSCA is statistically superior with regard to test suite size reduction compared to recent state-of-the-art strategies, including the original SCA, the particle swarm test generator (PSTG), adaptive particle swarm optimization (APSO) and the cuckoo search strategy (CS) at the 95% confidence level. However, concerning the comparison with discrete particle swarm optimization (DPSO), there is no significant difference in performance at the 95% confidence level. On a positive note, the QLSCA statistically outperforms the DPSO in certain configurations at the 90% confidence level.

##### Abstract (translated by Google)
正弦余弦算法（SCA）是一种新的基于种群的元启发式算法。除了利用正弦和余弦函数执行本地和全局搜索（因此名称为正余弦）之外，SCA还引入了多个随机和自适应参数以方便搜索过程。虽然它显示出有希望的结果，但由于采用固定切换概率和正弦和余弦函数的有界幅度（从-1到1），SCA的搜索过程易受局部最小/最大值的影响。在本文中，我们提出了一种新的混合Q学习正弦余弦的策略，称为Q学习正弦余弦算法（QLSCA）。在QLSCA中，我们消除了转换概率。相反，我们依靠Q学习算法（基于惩罚和奖励机制）来动态识别运行时的最佳操作。此外，我们将两个新的操作（L \'evy飞行运动和交叉）集成到QLSCA中，以便跳出局部最小/最大值并增强解决方案的多样性。为了评估其性能，我们采用QLSCA进行组合测试套件最小化问题。实验结果表明，与最近的最新策略相比，QLSCA在统计学上优于测试套件，包括原始SCA，粒子群测试生成器（PSTG），自适应粒子群优化（APSO）和布谷鸟搜索策略（CS）的置信度为95％。然而，关于与离散粒子群优化（DPSO）的比较，在95％置信水平下性能没有显着差异。值得肯定的是，在某些配置下，QLSCA在统计学上优于DPSO，其置信度为90％。

##### URL
[https://arxiv.org/abs/1805.00873](https://arxiv.org/abs/1805.00873)

##### PDF
[https://arxiv.org/pdf/1805.00873](https://arxiv.org/pdf/1805.00873)

