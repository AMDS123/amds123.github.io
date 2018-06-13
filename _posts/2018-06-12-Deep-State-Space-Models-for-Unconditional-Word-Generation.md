---
layout: post
title: "Deep State Space Models for Unconditional Word Generation"
date: 2018-06-12 14:19:48
categories: arXiv_CL
tags: arXiv_CL Text_Generation Inference
author: Florian Schmidt, Thomas Hofmann
mathjax: true
---

* content
{:toc}

##### Abstract
Autoregressive feedback is considered a necessity for successful unconditional text generation using stochastic sequence models. However, such feedback is known to introduce systematic biases into the training and it obscures a principle of generation: committing to global information and forgetting local nuances. We show that a non-autoregressive deep state space model with a clear separation of global and local uncertainty can be build from only two ingredients: An independent noise source and a deterministic transition function. Recent advances on flow-based variational inference allow training an evidence lower-bound without resorting to annealing, auxiliary losses or similar measures. The result is a highly interpretable generative model on par with a comparable auto-regressive model on the task of word generation.

##### Abstract (translated by Google)
自回归反馈被认为是使用随机序列模型成功实现无条件文本生成的必要条件。然而，已知这样的反馈将系统性偏见引入训练中，并且模糊了生成原则：致力于全球信息并忘记局部细微差别。我们表明，一个非自回归深层状态空间模型与全局和局部不确定性的明确分离可以从两个成分构建：一个独立的噪声源和一个确定性的转换函数。最近在基于流量的变分推理方面的进展允许在不借助退火，辅助损失或类似措施的情况下训练下限的证据。其结果是一个高度可解释的生成模型，与在字生成任务中可比较的自回归模型相当。

##### URL
[http://arxiv.org/abs/1806.04550](http://arxiv.org/abs/1806.04550)

##### PDF
[http://arxiv.org/pdf/1806.04550](http://arxiv.org/pdf/1806.04550)

