---
layout: post
title: "Prediction with a Short Memory"
date: 2018-05-27 01:30:15
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Vatsal Sharan, Sham Kakade, Percy Liang, Gregory Valiant
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of predicting the next observation given a sequence of past observations, and consider the extent to which accurate prediction requires complex algorithms that explicitly leverage long-range dependencies. Perhaps surprisingly, our positive results show that for a broad class of sequences, there is an algorithm that predicts well on average, and bases its predictions only on the most recent few observation together with a set of simple summary statistics of the past observations. Specifically, we show that for any distribution over observations, if the mutual information between past observations and future observations is upper bounded by $I$, then a simple Markov model over the most recent $I/\epsilon$ observations obtains expected KL error $\epsilon$---and hence $\ell_1$ error $\sqrt{\epsilon}$---with respect to the optimal predictor that has access to the entire past and knows the data generating distribution. For a Hidden Markov Model with $n$ hidden states, $I$ is bounded by $\log n$, a quantity that does not depend on the mixing time, and we show that the trivial prediction algorithm based on the empirical frequencies of length $O(\log n/\epsilon)$ windows of observations achieves this error, provided the length of the sequence is $d^{\Omega(\log n/\epsilon)}$, where $d$ is the size of the observation alphabet. 
 We also establish that this result cannot be improved upon, even for the class of HMMs, in the following two senses: First, for HMMs with $n$ hidden states, a window length of $\log n/\epsilon$ is information-theoretically necessary to achieve expected $\ell_1$ error $\sqrt{\epsilon}$. Second, the $d^{\Theta(\log n/\epsilon)}$ samples required to estimate the Markov model for an observation alphabet of size $d$ is necessary for any computationally tractable learning algorithm, assuming the hardness of strongly refuting a certain class of CSPs.

##### Abstract (translated by Google)
我们考虑在给定一系列过去的观测值的情况下预测下一次观测的问题，并考虑精确预测需要复杂算法明确利用长程相关性的程度。也许令人惊讶的是，我们的积极结果表明，对于一大类序列，有一种算法可以很好地平均预测，并且只根据最近的几次观察结果以及一组简单的过去观察统计数据进行预测。具体而言，我们表明，对于任何观测分布，如果过去观测值与未来观测值之间的相互信息上限为$ I $，那么在最近$ I / \ε观测值上的简单马尔科夫模型可以得到预期的KL误差$ \ epsilon $ ---，因此$ \ ell_1 $ error $ \ sqrt {\ epsilon} $ ---就可以访问整个过去并知道数据生成分布的最佳预测器而言。对于具有$ n $隐藏状态的隐马尔可夫模型，$ I $以$ \ log n $为界，这个数量不依赖于混合时间，我们证明了基于长度经验频率的平凡预测算法如果序列的长度为$ d ^ {\ Omega（\ log n / \ epsilon）} $，则$ O（\ log n / \ epsilon）$ windows的观察值可以达到这个误差，其中$ d $是观察字母表。
 我们还确定，即使对于HMM类，这个结果也不能在以下两个意义上得到改进：首先，对于隐藏状态为$ n $的HMM，窗口长度为$ \ log n / \ epsilon $是信息 - 理论上需要实现预期的$ \ ell_1 $错误$ \ sqrt {\ epsilon} $。其次，对于任何计算简便的学习算法来说，估计用于观察字母大小为$ d $的马尔科夫模型所需的$ d ^ {\ Theta（\ log n / \ epsilon）} $ samples是必要的，假设强烈拒绝某种类型的CSP。

##### URL
[http://arxiv.org/abs/1612.02526](http://arxiv.org/abs/1612.02526)

##### PDF
[http://arxiv.org/pdf/1612.02526](http://arxiv.org/pdf/1612.02526)

