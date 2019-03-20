---
layout: post
title: "Hyper-Parameter Sweep on AlphaZero General"
date: 2019-03-19 17:38:46
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Hui Wang, Michael Emmerich, Mike Preuss, Aske Plaat
mathjax: true
---

* content
{:toc}

##### Abstract
Since AlphaGo and AlphaGo Zero have achieved breakground successes in the game of Go, the programs have been generalized to solve other tasks. Subsequently, AlphaZero was developed to play Go, Chess and Shogi. In the literature, the algorithms are explained well. However, AlphaZero contains many parameters, and for neither AlphaGo, AlphaGo Zero nor AlphaZero, there is sufficient discussion about how to set parameter values in these algorithms. Therefore, in this paper, we choose 12 parameters in AlphaZero and evaluate how these parameters contribute to training. We focus on three objectives~(training loss, time cost and playing strength). For each parameter, we train 3 models using 3 different values~(minimum value, default value, maximum value). We use the game of play 6$\times$6 Othello, on the AlphaZeroGeneral open source re-implementation of AlphaZero. Overall, experimental results show that different values can lead to different training results, proving the importance of such a parameter sweep. We categorize these 12 parameters into time-sensitive parameters and time-friendly parameters. Moreover, through multi-objective analysis, this paper provides an insightful basis for further hyper-parameter optimization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08129](http://arxiv.org/abs/1903.08129)

##### PDF
[http://arxiv.org/pdf/1903.08129](http://arxiv.org/pdf/1903.08129)

