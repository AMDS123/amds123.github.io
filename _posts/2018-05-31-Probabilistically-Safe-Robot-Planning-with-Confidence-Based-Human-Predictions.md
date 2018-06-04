---
layout: post
title: "Probabilistically Safe Robot Planning with Confidence-Based Human Predictions"
date: 2018-05-31 21:47:34
categories: arXiv_RO
tags: arXiv_RO Tracking Prediction Quantitative
author: Jaime F. Fisac, Andrea Bajcsy, Sylvia L. Herbert, David Fridovich-Keil, Steven Wang, Claire J. Tomlin, Anca D. Dragan
mathjax: true
---

* content
{:toc}

##### Abstract
In order to safely operate around humans, robots can employ predictive models of human motion. Unfortunately, these models cannot capture the full complexity of human behavior and necessarily introduce simplifying assumptions. As a result, predictions may degrade whenever the observed human behavior departs from the assumed structure, which can have negative implications for safety. In this paper, we observe that how "rational" human actions appear under a particular model can be viewed as an indicator of that model's ability to describe the human's current motion. By reasoning about this model confidence in a real-time Bayesian framework, we show that the robot can very quickly modulate its predictions to become more uncertain when the model performs poorly. Building on recent work in provably-safe trajectory planning, we leverage these confidence-aware human motion predictions to generate assured autonomous robot motion. Our new analysis combines worst-case tracking error guarantees for the physical robot with probabilistic time-varying human predictions, yielding a quantitative, probabilistic safety certificate. We demonstrate our approach with a quadcopter navigating around a human.

##### Abstract (translated by Google)
为了安全地操作人类，机器人可以使用人体运动的预测模型。不幸的是，这些模型不能捕捉到人类行为的完整复杂性，并且必然引入简化的假设。因此，只要观察到的人类行为偏离假设结构，预测就会下降，这会对安全产生负面影响。在本文中，我们观察到如何在特定模型下出现“理性”人类行为可以被看作是该模型描述人类当前动作的能力的一个指标。通过对实时贝叶斯框架中的模型置信度进行推理，我们发现机器人可以非常快速地调整其预测，从而在模型性能不佳时变得更加不确定。基于最近在可证实的安全轨迹规划方面的工作，我们利用这些置信度感知的人体运动预测来生成有保证的自主机器人运动。我们最新的分析将物理机器人的最坏情况跟踪误差保证与概率性时变人体预测相结合，产生定量的概率安全证书。我们用四轴飞行器在人体周围展示我们的方法。

##### URL
[http://arxiv.org/abs/1806.00109](http://arxiv.org/abs/1806.00109)

##### PDF
[http://arxiv.org/pdf/1806.00109](http://arxiv.org/pdf/1806.00109)

