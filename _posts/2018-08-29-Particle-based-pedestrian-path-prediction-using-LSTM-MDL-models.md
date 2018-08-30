---
layout: post
title: "Particle-based pedestrian path prediction using LSTM-MDL models"
date: 2018-08-29 07:02:13
categories: arXiv_CV
tags: arXiv_CV RNN Prediction Relation
author: Ronny Hug, Stefan Becker, Wolfgang H&#xfc;bner, Michael Arens
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks are able to learn complex long-term relationships from sequential data and output a pdf over the state space. Therefore, recurrent models are a natural choice to address path prediction tasks, where a trained model is used to generate future expectations from past observations. When applied to security applications, like predicting the path of pedestrians for risk assessment, a point-wise greedy (ML) evaluation of the output pdf is not feasible, since the environment often allows multiple choices. Therefore, a robust risk assessment has to take all options into account, even if they are overall not very likely. 
 Towards this end, a combination of particle filter sampling strategies and a LSTM-MDL model is proposed to address a multi-modal path prediction task. The capabilities and viability of the proposed approach are evaluated on several synthetic test conditions, yielding the counter-intuitive result that the simplest approach performs best. Further, the feasibility of the proposed approach is illustrated on several real world scenes.

##### Abstract (translated by Google)
循环神经网络能够从顺序数据中学习复杂的长期关系，并在状态空间上输出pdf。因此，递归模型是解决路径预测任务的自然选择，其中训练模型用于根据过去的观察产生未来期望。当应用于安全应用程序时，例如预测行人进行风险评估的路径，输出pdf的逐点贪心（ML）评估是不可行的，因为环境通常允许多种选择。因此，强有力的风险评估必须考虑所有选项，即使它们总体上不太可能。
 为此，提出了粒子滤波器采样策略和LSTM-MDL模型的组合以解决多模态路径预测任务。在几个综合测试条件下评估所提出方法的能力和可行性，产生反直觉结果，即最简单的方法表现最佳。此外，在几个真实场景中说明了所提出方法的可行性。

##### URL
[http://arxiv.org/abs/1804.05546](http://arxiv.org/abs/1804.05546)

##### PDF
[http://arxiv.org/pdf/1804.05546](http://arxiv.org/pdf/1804.05546)

