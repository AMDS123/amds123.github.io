---
layout: post
title: "Lower Bounds for Searching Robots, some Faulty"
date: 2018-05-21 16:50:20
categories: arXiv_RO
tags: arXiv_RO
author: Andrey Kupavskii, Emo Welzl
mathjax: true
---

* content
{:toc}

##### Abstract
Suppose we are sending out $k$ robots from $0$ to search the real line at constant speed (with turns) to find a target at an unknown location; $f$ of the robots are faulty, meaning that they fail to report the target although visiting its location (called crash type). The goal is to find the target in time at most $\lambda |d|$, if the target is located at $d$, $|d| \ge 1$, for $\lambda$ as small as possible. We show that this cannot be achieved for $$\lambda &lt; 2\frac{\rho^\rho}{(\rho-1)^{\rho-1}}+1,~~ \rho := \frac{2(f+1)}{k}~, $$ which is tight due to earlier work (see J. Czyzowitz, E. Kranakis, D. Krizanc, L. Narayanan, J. Opatrny, PODC'16, where this problem was introduced). This also gives some better than previously known lower bounds for so-called Byzantine-type faulty robots that may actually wrongly report a target. 
 In the second part of the paper, we deal with the $m$-rays generalization of the problem, where the hidden target is to be detected on $m$ rays all emanating at the same point. Using a generalization of our methods, along with a useful relaxation of the original problem, we establish a tight lower for this setting as well (as above, with $\rho := m(f+1)/k$). When specialized to the case $f=0$, this resolves the question on parallel search on $m$ rays, posed by three groups of scientists some 15 to 30 years ago: by Baeza-Yates, Culberson, and Rawlins; by Kao, Ma, Sipser, and Yin; and by Bernstein, Finkelstein, and Zilberstein. The $m$-rays generalization is known to have connections to other, seemingly unrelated, problems, including hybrid algorithms for on-line problems, and so-called contract algorithms.

##### Abstract (translated by Google)
假设我们从$ 0 $发出$ k $机器人以恒速搜索实线（轮流）以在未知位置找到目标; $ f $的机器人有故障，这意味着它们虽然访问了它的位置（称为崩溃类型），但未能报告目标。我们的目标是要及时发现目标在$ \ lambda | d | $的情况下，如果目标位于$ d $，$ | d | \ ge 1 $，对于$ \ lambda $越小越好。我们证明，这对于$$ \ lambda＆lt; 2（f + 1）} {1，...，1}，其中{\ rho ^ {rho-1}由于之前的工作，这是紧密的（参见J.Czyzowitz，E.Kranakis，D.Krizanc，L.Narayanan，J.Opatrny，PODC'16，其中引入了这个问题）。这也为所谓的拜占庭式故障机器人提供了比先前已知的更低的下限，其可能实际上错误地报告了目标。
 在本文的第二部分，我们讨论了这个问题的$ m $  - 概括，其中隐藏的目标将在同一点发现的$ m $射线上被检测到。使用我们方法的一般化，以及对原始问题的有用放松，我们也为这个设置建立了一个较低的下限（如上面的$ \ rho：= m（f + 1）/ k $）。当专门针对$ f = 0 $的情况时，这解决了在15至30年前由三组科学家提出的对$ m $ rays进行并行搜索的问题：由Baeza-Yates，Culberson和Rawlins提出; Kao，Ma，Sipser和Yin;和伯恩斯坦，芬克尔斯坦和齐尔伯斯坦。已知$ m $ -rays泛化与其他看似无关的问题有关，包括用于在线问题的混合算法和所谓的合约算法。

##### URL
[http://arxiv.org/abs/1707.05077](http://arxiv.org/abs/1707.05077)

##### PDF
[http://arxiv.org/pdf/1707.05077](http://arxiv.org/pdf/1707.05077)

