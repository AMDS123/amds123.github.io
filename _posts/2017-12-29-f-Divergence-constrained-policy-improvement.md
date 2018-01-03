---
layout: post
title: "f-Divergence constrained policy improvement"
date: 2017-12-29 23:07:26
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Boris Belousov, Jan Peters
mathjax: true
---

* content
{:toc}

##### Abstract
To ensure stability of learning, state-of-the-art generalized policy iteration algorithms augment the policy improvement step with a trust region constraint bounding the information loss. The size of the trust region is commonly determined by the Kullback-Leibler (KL) divergence, which not only captures the notion of distance well but also yields closed-form solutions. In this paper, we consider a more general class of f-divergences and derive the corresponding policy update rules. The generic solution is expressed through the derivative of the convex conjugate function to f and includes the KL solution as a special case. Within the class of f-divergences, we further focus on a one-parameter family of {\alpha}-divergences to study effects of the choice of divergence on policy improvement. Previously known as well as new policy updates emerge for different values of {\alpha}. We show that every type of policy update comes with a compatible policy evaluation resulting from the chosen f-divergence. Interestingly, the mean-squared Bellman error minimization is closely related to policy evaluation with the Pearson $\chi^2$-divergence penalty, while the KL divergence results in the soft-max policy update and a log-sum-exp critic. We carry out asymptotic analysis of the solutions for different values of {\alpha} and demonstrate the effects of using different divergence functions on a multi-armed bandit problem and on common standard reinforcement learning problems.

##### Abstract (translated by Google)
为了确保学习的稳定性，最先进的广义策略迭代算法通过信任域约束约束信息丢失来增强策略改进步骤。信赖域的大小通常由Kullback-Leibler（KL）分歧决定，它不仅捕捉距离的概念，而且产生封闭的解决方案。在本文中，我们考虑一个更一般的f-散度类并推导出相应的策略更新规则。通用解是通过将凸共轭函数导出为f来表示的，并且包括作为特例的KL解。在f-散度的类别中，我们进一步关注一个单参数的{alpha}  - 散度家族来研究选择分歧对政策改进的影响。之前已知的以及新的政策更新出现了{\ alpha}的不同值。我们显示，每一种政策更新都带有一个兼容的政策评估，由选择的f-散度产生。有趣的是，均方Bellman误差最小化与Pearson $ \ chi ^ 2 $ -divergence惩罚的政策评估密切相关，而KL分歧导致了软最大策略更新和log-sum-exp评论。我们对{\ alpha}不同值的解进行渐近分析，并证明不同发散函数对多臂匪问题和共同标准强化学习问题的影响。

##### URL
[http://arxiv.org/abs/1801.00056](http://arxiv.org/abs/1801.00056)

##### PDF
[http://arxiv.org/pdf/1801.00056](http://arxiv.org/pdf/1801.00056)

