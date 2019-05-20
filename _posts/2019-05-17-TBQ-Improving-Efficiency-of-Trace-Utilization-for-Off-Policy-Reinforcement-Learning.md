---
layout: post
title: "TBQ: Improving Efficiency of Trace Utilization for Off-Policy Reinforcement Learning"
date: 2019-05-17 14:36:48
categories: arXiv_AI
tags: arXiv_AI Face Reinforcement_Learning
author: Longxiang Shi, Shijian Li, Longbing Cao, Long Yang, Gang Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Off-policy reinforcement learning with eligibility traces is challenging because of the discrepancy between target policy and behavior policy. One common approach is to measure the difference between two policies in a probabilistic way, such as importance sampling and tree-backup. However, existing off-policy learning methods based on probabilistic policy measurement are inefficient when utilizing traces under a greedy target policy, which is ineffective for control problems. The traces are cut immediately when a non-greedy action is taken, which may lose the advantage of eligibility traces and slow down the learning process. Alternatively, some non-probabilistic measurement methods such as General Q($\lambda$) and Naive Q($\lambda$) never cut traces, but face convergence problems in practice. To address the above issues, this paper introduces a new method named TBQ($\sigma$), which effectively unifies the tree-backup algorithm and Naive Q($\lambda$). By introducing a new parameter $\sigma$ to illustrate the \emph{degree} of utilizing traces, TBQ($\sigma$) creates an effective integration of TB($\lambda$) and Naive Q($\lambda$) and continuous role shift between them. The contraction property of TB($\sigma$) is theoretically analyzed for both policy evaluation and control settings. We also derive the online version of TBQ($\sigma$) and give the convergence proof. We empirically show that, for $\epsilon\in(0,1]$ in $\epsilon$-greedy policies, there exists some degree of utilizing traces for $\lambda\in[0,1]$, which can improve the efficiency in trace utilization for off-policy reinforcement learning, to both accelerate the learning process and improve the performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07237](http://arxiv.org/abs/1905.07237)

##### PDF
[http://arxiv.org/pdf/1905.07237](http://arxiv.org/pdf/1905.07237)

