---
layout: post
title: "A Reinforcement Learning Approach to the View Planning Problem"
date: 2016-11-18 20:26:51
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Optimization
author: Mustafa Devrim Kaba, Mustafa Gokhan Uzunbas, Ser Nam Lim
mathjax: true
---

* content
{:toc}

##### Abstract
We present a Reinforcement Learning (RL) solution to the view planning problem (VPP), which generates a sequence of view points that are capable of sensing all accessible area of a given object represented as a 3D model. In doing so, the goal is to minimize the number of view points, making the VPP a class of set covering optimization problem (SCOP). The SCOP is NP-hard, and the inapproximability results tell us that the greedy algorithm provides the best approximation that runs in polynomial time. In order to find a solution that is better than the greedy algorithm, (i) we introduce a novel score function by exploiting the geometry of the 3D model, (ii) we model an intuitive human approach to VPP using this score function, and (iii) we cast VPP as a Markovian Decision Process (MDP), and solve the MDP in RL framework using well-known RL algorithms. In particular, we use SARSA, Watkins-Q and TD with function approximation to solve the MDP. We compare the results of our method with the baseline greedy algorithm in an extensive set of test objects, and show that we can out-perform the baseline in almost all cases.

##### Abstract (translated by Google)
我们提出了视图规划问题（VPP）的强化学习（RL）解决方案，该解决方案生成一系列视点，能够感知表示为3D模型的给定对象的所有可访问区域。这样做的目的是最小化视点的数量，使得VPP成为覆盖优化问题（SCOP）的一类。 SCOP是NP-hard，不可计算性结果告诉我们，贪婪算法提供了在多项式时间运行的最佳近似。为了找到比贪婪算法更好的解决方案，（i）我们通过利用三维模型的几何结构来引入一个新的分数函数，（ii）我们使用这个分数函数为VPP建模一个直观的人类方法， iii）将VPP作为马尔可夫决策过程（MDP），并使用众所周知的RL算法解决RL框架中的MDP问题。具体而言，我们使用SARSA，Watkins-Q和TD进行函数逼近来求解MDP。我们在广泛的测试对象集中比较了我们的方法和基线贪婪算法的结果，并且显示几乎在所有情况下我们都可以超出基线。

##### URL
[https://arxiv.org/abs/1610.06204](https://arxiv.org/abs/1610.06204)

##### PDF
[https://arxiv.org/pdf/1610.06204](https://arxiv.org/pdf/1610.06204)

