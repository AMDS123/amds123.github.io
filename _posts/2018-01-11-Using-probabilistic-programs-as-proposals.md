---
layout: post
title: "Using probabilistic programs as proposals"
date: 2018-01-11 02:07:39
categories: arXiv_AI
tags: arXiv_AI Knowledge Inference
author: Marco F. Cusumano-Towner, Vikash K. Mansinghka
mathjax: true
---

* content
{:toc}

##### Abstract
Monte Carlo inference has asymptotic guarantees, but can be slow when using generic proposals. Handcrafted proposals that rely on user knowledge about the posterior distribution can be efficient, but are difficult to derive and implement. This paper proposes to let users express their posterior knowledge in the form of \emph{proposal programs}, which are samplers written in probabilistic programming languages. One strategy for writing good proposal programs is to combine domain-specific heuristic algorithms with neural network models. The heuristics identify high probability regions, and the neural networks model the posterior uncertainty around the outputs of the algorithm. Proposal programs can be used as proposal distributions in importance sampling and Metropolis-Hastings samplers without sacrificing asymptotic consistency, and can be optimized offline using inference compilation. Support for optimizing and using proposal programs is easily implemented in a sampling-based probabilistic programming runtime. The paper illustrates the proposed technique with a proposal program that combines RANSAC and neural networks to accelerate inference in a Bayesian linear regression with outliers model.

##### Abstract (translated by Google)
蒙特卡罗推断具有渐近的保证，但在使用通用建议时可能会很慢。依赖用户对后验分布知识的手工建议可能是有效的，但难以推导和实施。本文提出让用户以\ emph {提案程序}的形式表达他们的后验知识，这些程序是用概率编程语言编写的采样器。编写好的提案程序的一个策略是将领域特定的启发式算法与神经网络模型相结合。启发式识别高概率区域，神经网络模拟算法输出的后验不确定性。可以在不牺牲渐近一致性的情况下将提议程序用作重要抽样和Metropolis-Hastings采样器中的提案分布，并且可以使用推断编译进行离线优化。支持优化和使用提案程序很容易在基于抽样的概率编程运行时中实现。本文阐述了提出的技术，提出了一种将RANSAC和神经网络相结合的方案，以加速Bayes线性回归中的推理与异常值模型。

##### URL
[http://arxiv.org/abs/1801.03612](http://arxiv.org/abs/1801.03612)

##### PDF
[http://arxiv.org/pdf/1801.03612](http://arxiv.org/pdf/1801.03612)

