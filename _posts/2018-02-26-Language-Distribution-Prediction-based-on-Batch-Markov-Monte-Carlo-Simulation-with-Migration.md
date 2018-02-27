---
layout: post
title: "Language Distribution Prediction based on Batch Markov Monte Carlo Simulation with Migration"
date: 2018-02-26 07:52:30
categories: arXiv_CL
tags: arXiv_CL Prediction
author: XingYu Fu, ZiYi Yang, XiuWen Duan
mathjax: true
---

* content
{:toc}

##### Abstract
Language spreading is a complex mechanism that involves issues like culture, economics, migration, population etc. In this paper, we propose a set of methods to model the dynamics of the spreading system. To model the randomness of language spreading, we propose the Batch Markov Monte Carlo Simulation with Migration(BMMCSM) algorithm, in which each agent is treated as a language stack. The agent learns languages and migrates based on the proposed Batch Markov Property according to the transition matrix T and migration matrix M. Since population plays a crucial role in language spreading, we also introduce the Mortality and Fertility Mechanism, which controls the birth and death of the simulated agents, into the BMMCSM algorithm. The simulation results of BMMCSM show that the numerical and geographic distribution of languages varies across the time. The change of distribution fits the world cultural and economic development trend. Next, when we construct Matrix T, there are some entries of T can be directly calculated from historical statistics while some entries of T is unknown. Thus, the key to the success of the BMMCSM lies in the accurate estimation of transition matrix T by estimating the unknown entries of T under the supervision of the known entries. To achieve this, we first construct a 20 by 20 by 5 factor tensor X to characterize each entry of T. Then we train a Random Forest Regressor on the known entries of T and use the trained regressor to predict the unknown entries. The reason why we choose Random Forest(RF) is that, compared to Single Decision Tree, it conquers the problem of over fitting and the Shapiro test also suggests that the residual of RF subjects to the Normal distribution.

##### Abstract (translated by Google)
语言传播是一个涉及文化，经济，移民，人口等问题的复杂机制。本文提出了一套模拟传播系统动力学的方法。为了模拟语言传播的随机性，我们提出了具有迁移的批量马尔可夫蒙特卡罗模拟（BMMCSM）算法，其中每个代理被视为语言堆栈。智能体根据转移矩阵T和迁移矩阵M，根据提出的批量马尔可夫性学习语言和迁移。由于人口在语言传播中起着至关重要的作用，因此我们还介绍了死亡率和生育机制，它控制着生命和死亡模拟代理，转换成BMMCSM算法。 BMMCSM的模拟结果表明，语言的数字和地理分布随时间而变化。分销的变化符合世界文化和经济发展的趋势。接下来，当我们构造Matrix T时，有一些T的条目可以直接从历史统计中计算出来，而T的某些条目是未知的。因此，BMMCSM成功的关键在于通过在已知条目的监督下估计T的未知条目来准确估计转移矩阵T.为了达到这个目的，我们首先构造一个20乘20乘5的因子张量X来表征T的每个入口。然后，我们对T的已知入口训练一个随机森林回归器，并使用训练后的回归器来预测未知入口。我们选择随机森林（RF）的原因是，与单一决策树相比，它克服了过拟合的问题，夏皮罗测试也表明射频主体的残差与正态分布有关。

##### URL
[http://arxiv.org/abs/1802.09189](http://arxiv.org/abs/1802.09189)

##### PDF
[http://arxiv.org/pdf/1802.09189](http://arxiv.org/pdf/1802.09189)

