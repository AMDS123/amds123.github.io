---
layout: post
title: "On-Line Learning of Linear Dynamical Systems: Exponential Forgetting in Kalman Filters"
date: 2018-09-16 13:21:49
categories: arXiv_AI
tags: arXiv_AI Prediction
author: Mark Kozdoba, Jakub Marecek, Tigran Tchrakian, Shie Mannor
mathjax: true
---

* content
{:toc}

##### Abstract
Kalman filter is a key tool for time-series forecasting and analysis. We show that the dependence of a prediction of Kalman filter on the past is decaying exponentially, whenever the process noise is non-degenerate. Therefore, Kalman filter may be approximated by regression on a few recent observations. Surprisingly, we also show that having some process noise is essential for the exponential decay. With no process noise, it may happen that the forecast depends on all of the past uniformly, which makes forecasting more difficult. 
 Based on this insight, we devise an on-line algorithm for improper learning of a linear dynamical system (LDS), which considers only a few most recent observations. We use our decay results to provide the first regret bounds w.r.t. to Kalman filters within learning an LDS. That is, we compare the results of our algorithm to the best, in hindsight, Kalman filter for a given signal. Also, the algorithm is practical: its per-update run-time is linear in the regression depth.

##### Abstract (translated by Google)
卡尔曼滤波器是时间序列预测和分析的关键工具。我们表明，只要过程噪声是非简并的，卡尔曼滤波器预测对过去的依赖性就会呈指数衰减。因此，卡尔曼滤波器可以通过对最近几次观察的回归来近似。令人惊讶的是，我们还表明，一些过程噪声对于指数衰减至关重要。在没有过程噪声的情况下，可能会发生预测依赖于过去的所有过去，这使得预测更加困难。
 基于这种见解，我们设计了一种用于线性动力系统（LDS）的不正确学习的在线算法，该算法仅考虑了一些最近的观察。我们使用我们的衰变结果来提供第一个遗憾的界限w.r.t.学习LDS的卡尔曼滤波器。也就是说，我们将算法的结果与事后最佳卡尔曼滤波器的最佳结果进行比较。此外，该算法是实用的：其每次更新运行时在回归深度中是线性的。

##### URL
[http://arxiv.org/abs/1809.05870](http://arxiv.org/abs/1809.05870)

##### PDF
[http://arxiv.org/pdf/1809.05870](http://arxiv.org/pdf/1809.05870)

