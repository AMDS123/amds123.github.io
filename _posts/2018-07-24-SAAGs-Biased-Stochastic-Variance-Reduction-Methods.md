---
layout: post
title: "SAAGs: Biased Stochastic Variance Reduction Methods"
date: 2018-07-24 07:36:21
categories: arXiv_AI
tags: arXiv_AI Tracking Optimization
author: Vinod Kumar Chauhan, Anuj Sharma, Kalpana Dahiya
mathjax: true
---

* content
{:toc}

##### Abstract
Stochastic optimization is one of the effective approach to deal with the large-scale machine learning problems and the recent research has focused on reduction of variance, caused by the noisy approximations of the gradients, and momentum acceleration. In this paper, we have proposed simple variants of SAAG-I and II (Stochastic Average Adjusted Gradient) \cite{Chauhan2017Saag}, called SAAG-III and IV, respectively. Unlike SAAG-I, starting point is set to average of previous epoch in SAAG-III, and unlike SAAG-II, the snap point and starting point are set to average and last iterate of previous epoch, respectively. To determine the step size, we introduce Stochastic Backtracking-Armijo line Search (SBAS) which performs line search only on selected mini-batch of data points. Since backtracking line search is not suitable for large-scale problems and the constants used to find the step size, like Lipschitz constant, are not always available so SBAS could be very effective in such cases. We also extend SAAGs (I, II, III, IV), to solve non-smooth problems and design two update rules for smooth and non-smooth problems. Moreover, our theoretical results prove linear convergence of SAAG-IV for all the four combinations of smoothness and strong-convexity, in expectation. Finally, our experimental studies prove the efficacy of proposed methods against the state-of-art techniques, like, SVRG and VR-SGD.

##### Abstract (translated by Google)
随机优化是处理大规模机器学习问题的有效方法之一，最近的研究主要集中在由梯度的噪声近似和动量加速引起的方差减少。在本文中，我们提出了SAAG-I和II（随机平均调整梯度）\ cite {Chauhan2017Saag}的简单变体，分别称为SAAG-III和IV。与SAAG-I不同，起始点设置为SAAG-III中前一个纪元的平均值，与SAAG-II不同，捕捉点和起始点分别设置为上一个纪元的平均值和最后一个迭代值。为了确定步长，我们引入了随机回溯 -  Armijo线搜索（SBAS），它仅对选定的小批量数据点执行线搜索。由于回溯线搜索不适合大规模问题，并且用于找到步长的常数（如Lipschitz常数）并不总是可用，因此SBAS在这种情况下可能非常有效。我们还扩展了SAAG（I，II，III，IV），以解决非平滑问题，并为平滑和非平滑问题设计两个更新规则。此外，我们的理论结果证明了SAAG-IV在所有四种平滑度和强凸度组合中的线性收敛性。最后，我们的实验研究证明了所提方法对SVRG和VR-SGD等最先进技术的有效性。

##### URL
[https://arxiv.org/abs/1807.08934](https://arxiv.org/abs/1807.08934)

##### PDF
[https://arxiv.org/pdf/1807.08934](https://arxiv.org/pdf/1807.08934)

