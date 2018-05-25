---
layout: post
title: "Learning and Testing Causal Models with Interventions"
date: 2018-05-24 14:31:09
categories: arXiv_AI
tags: arXiv_AI
author: Jayadev Acharya, Arnab Bhattacharyya, Constantinos Daskalakis, Saravanan Kandasamy
mathjax: true
---

* content
{:toc}

##### Abstract
We consider testing and learning problems on causal Bayesian networks as defined by Pearl (Pearl, 2009). Given a causal Bayesian network $\mathcal{M}$ on a graph with $n$ discrete variables and bounded in-degree and bounded `confounded components', we show that $O(\log n)$ interventions on an unknown causal Bayesian network $\mathcal{X}$ on the same graph, and $\tilde{O}(n/\epsilon^2)$ samples per intervention, suffice to efficiently distinguish whether $\mathcal{X}=\mathcal{M}$ or whether there exists some intervention under which $\mathcal{X}$ and $\mathcal{M}$ are farther than $\epsilon$ in total variation distance. We also obtain sample/time/intervention efficient algorithms for: (i) testing the identity of two unknown causal Bayesian networks on the same graph; and (ii) learning a causal Bayesian network on a given graph. Although our algorithms are non-adaptive, we show that adaptivity does not help in general: $\Omega(\log n)$ interventions are necessary for testing the identity of two unknown causal Bayesian networks on the same graph, even adaptively. Our algorithms are enabled by a new subadditivity inequality for the squared Hellinger distance between two causal Bayesian networks.

##### Abstract (translated by Google)
我们考虑测试和学习由Pearl定义的因果贝叶斯网络问题（Pearl，2009）。给定一个具有$ n $离散变量和有界入度和有界“混淆分量”的图上的因果贝叶斯网络$ \ mathcal {M} $，我们证明$ O（\ log n）$对一个未知的因果贝叶斯网络$ \ mathcal {X} $在同一个图上，$ \ tilde {O}（n / \ epsilon ^ 2）$ samples每个干预，足以有效区分$ \ mathcal {X} = \ mathcal {M} $或者是否存在一些干预，其中$ \ mathcal {X} $和$ \ mathcal {M} $在总变化距离中远远超过$ \ epsilon $。我们还获得样本/时间/干预高效算法：（i）在同一图上测试两个未知因果贝叶斯网络的身份;和（ii）在给定的图表上学习因果贝叶斯网络。虽然我们的算法是非自适应的，但是我们表明自适应对一般情况没有帮助：为了在同一个图上测试两个未知因果贝叶斯网络的身份，甚至是自适应地，都需要$ \ Omega（\ log n）$干预。我们的算法通过对两个因果贝叶斯网络之间平方Hellinger距离的新的子可加性不等式来实现。

##### URL
[http://arxiv.org/abs/1805.09697](http://arxiv.org/abs/1805.09697)

##### PDF
[http://arxiv.org/pdf/1805.09697](http://arxiv.org/pdf/1805.09697)

