---
layout: post
title: "A Bayesian Clearing Mechanism for Combinatorial Auctions"
date: 2017-12-14 15:34:42
categories: arXiv_AI
tags: arXiv_AI
author: Gianluca Brero, Sébastien Lahaie
mathjax: true
---

* content
{:toc}

##### Abstract
We cast the problem of combinatorial auction design in a Bayesian framework in order to incorporate prior information into the auction process and minimize the number of rounds to convergence. We first develop a generative model of agent valuations and market prices such that clearing prices become maximum a posteriori estimates given observed agent valuations. This generative model then forms the basis of an auction process which alternates between refining estimates of agent valuations and computing candidate clearing prices. We provide an implementation of the auction using assumed density filtering to estimate valuations and expectation maximization to compute prices. An empirical evaluation over a range of valuation domains demonstrates that our Bayesian auction mechanism is highly competitive against the combinatorial clock auction in terms of rounds to convergence, even under the most favorable choices of price increment for this baseline.

##### Abstract (translated by Google)
我们将贝叶斯框架下的组合拍卖设计问题，以便将先前的信息纳入拍卖过程，并最小化收敛的轮数。我们首先发展了一个代理商估值和市场价格的生成模型，以便在观察到代理商估值的情况下，清算价格成为最大后验估计值。这个生成模型就构成了拍卖过程的基础，它在提炼代理人估值和计算候选清算价格之间交替进行。我们提供一个实施拍卖使用假设密度过滤估计估价和期望最大化来计算价格。对一系列估值领域进行的实证评估表明，即使在这个基线的价格增量的最有利的选择下，我们的贝叶斯拍卖机制对于组合时钟拍卖在收敛回合方面是高度竞争的。

##### URL
[https://arxiv.org/abs/1712.05291](https://arxiv.org/abs/1712.05291)

##### PDF
[https://arxiv.org/pdf/1712.05291](https://arxiv.org/pdf/1712.05291)

