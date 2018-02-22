---
layout: post
title: "Clipped Action Policy Gradient"
date: 2018-02-21 13:39:28
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Yasuhiro Fujita, Shin-ichi Maeda
mathjax: true
---

* content
{:toc}

##### Abstract
Many continuous control tasks have bounded action spaces and clip out-of-bound actions before execution. Policy gradient methods often optimize policies as if actions were not clipped. We propose clipped action policy gradient (CAPG) as an alternative policy gradient estimator that exploits the knowledge of actions being clipped to reduce the variance in estimation. We prove that CAPG is unbiased and achieves lower variance than the original estimator that ignores action bounds. Experimental results demonstrate that CAPG generally outperforms the original estimator, indicating its promise as a better policy gradient estimator for continuous control tasks.

##### Abstract (translated by Google)
许多连续的控制任务在执行之前已经限定了动作空间并且限制了不受约束的动作。策略渐变方法通常优化策略，就好像动作未被剪切一样。我们提出限幅行动策略梯度（CAPG）作为替代策略梯度估计器，利用被削减的行为知识来减少估计方差。我们证明了CAPG是无偏的，并且与忽略动作范围的原始估计量相比，实现了更低的方差。实验结果表明，CAPG通常优于原始估计量，表明其作为连续控制任务的更好策略梯度估计量的前景。

##### URL
[http://arxiv.org/abs/1802.07564](http://arxiv.org/abs/1802.07564)

##### PDF
[http://arxiv.org/pdf/1802.07564](http://arxiv.org/pdf/1802.07564)

