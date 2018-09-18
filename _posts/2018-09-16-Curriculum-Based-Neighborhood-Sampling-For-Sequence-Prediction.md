---
layout: post
title: "Curriculum-Based Neighborhood Sampling For Sequence Prediction"
date: 2018-09-16 17:17:56
categories: arXiv_CL
tags: arXiv_CL Language_Model Prediction
author: James O&#x27; Neill, Danushka Bollegala
mathjax: true
---

* content
{:toc}

##### Abstract
The task of multi-step ahead prediction in language models is challenging considering the discrepancy between training and testing. At test time, a language model is required to make predictions given past predictions as input, instead of the past targets that are provided during training. This difference, known as exposure bias, can lead to the compounding of errors along a generated sequence at test time. 
 In order to improve generalization in neural language models and address compounding errors, we propose a curriculum learning based method that gradually changes an initially deterministic teacher policy to a gradually more stochastic policy, which we refer to as \textit{Nearest-Neighbor Replacement Sampling}. A chosen input at a given timestep is replaced with a sampled nearest neighbor of the past target with a truncated probability proportional to the cosine similarity between the original word and its top $k$ most similar words. This allows the teacher to explore alternatives when the teacher provides a sub-optimal policy or when the initial policy is difficult for the learner to model. The proposed strategy is straightforward, online and requires little additional memory requirements. We report our main findings on two language modelling benchmarks and find that the proposed approach performs particularly well when used in conjunction with scheduled sampling, that too attempts to mitigate compounding errors in language models.

##### Abstract (translated by Google)
考虑到训练和测试之间的差异，语言模型中的多步预测任务具有挑战性。在测试时，需要一种语言模型来预测过去的预测作为输入，而不是在训练期间提供的过去目标。这种差异称为暴露偏差，可能导致在测试时沿着生成的序列混合错误。
 为了改进神经语言模型的泛化和解决复合错误，我们提出了一种基于课程学习的方法，逐步将初始确定性的教师政策改为逐渐更加随机的政策，我们将其称为\ textit {最近邻替换抽样} 。在给定时间步长处的所选输入被替换为过去目标的采样最近邻居，其截断概率与原始单词与其顶部$ k $最相似单词之间的余弦相似性成比例。这允许教师在教师提供次优策略时或者当初始策略难以使学习者建模时探索替代方案。所提出的策略很简单，在线并且几乎不需要额外的内存。我们在两种语言建模基准测试中报告了我们的主要发现，并发现所提出的方法在与预定采样结合使用时表现特别好，这也试图减轻语言模型中的复合错误。

##### URL
[http://arxiv.org/abs/1809.05916](http://arxiv.org/abs/1809.05916)

##### PDF
[http://arxiv.org/pdf/1809.05916](http://arxiv.org/pdf/1809.05916)

