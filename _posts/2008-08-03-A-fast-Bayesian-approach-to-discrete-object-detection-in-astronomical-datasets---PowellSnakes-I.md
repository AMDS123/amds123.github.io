---
layout: post
title: "A fast Bayesian approach to discrete object detection in astronomical datasets - PowellSnakes I"
date: 2008-08-03 03:00:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Pedro Carvalho, Graca Rocha, M.P.Hobson
mathjax: true
---

* content
{:toc}

##### Abstract
A new fast Bayesian approach is introduced for the detection of discrete objects immersed in a diffuse background. This new method, called PowellSnakes, speeds up traditional Bayesian techniques by: i) replacing the standard form of the likelihood for the parameters characterizing the discrete objects by an alternative exact form that is much quicker to evaluate; ii) using a simultaneous multiple minimization code based on Powell's direction set algorithm to locate rapidly the local maxima in the posterior; and iii) deciding whether each located posterior peak corresponds to a real object by performing a Bayesian model selection using an approximate evidence value based on a local Gaussian approximation to the peak. The construction of this Gaussian approximation also provides the covariance matrix of the uncertainties in the derived parameter values for the object in question. This new approach provides a speed up in performance by a factor of `hundreds' as compared to existing Bayesian source extraction methods that use MCMC to explore the parameter space, such as that presented by Hobson & McLachlan. We illustrate the capabilities of the method by applying to some simplified toy models. Furthermore PowellSnakes has the advantage of consistently defining the threshold for acceptance/rejection based on priors which cannot be said of the frequentist methods. We present here the first implementation of this technique (Version-I). Further improvements to this implementation are currently under investigation and will be published shortly. The application of the method to realistic simulated Planck observations will be presented in a forthcoming publication.

##### Abstract (translated by Google)
引入一种新的快速贝叶斯方法来检测浸没在漫反射背景中的离散物体。这种称为PowellSnakes的新方法通过以下方式加速了传统的贝叶斯技术：i）用替代的精确形式代替表征离散对象的参数的可能性的标准形式，其速度快得多; ii）使用基于鲍威尔方向集算法的同时多重最小化代码快速地定位后验中的局部最大值;以及iii）通过基于峰值的局部高斯近似使用近似证据值执行贝叶斯模型选择，来确定每个定位的后峰值是否对应于真实对象。这种高斯近似的构造还提供了所讨论的对象的导出参数值中的不确定性的协方差矩阵。与使用MCMC探索参数空间的现有贝叶斯源提取方法（如Hobson＆McLachlan提出的方法）相比，这种新方法的性能提高了几百倍。我们通过应用一些简化的玩具模型来说明该方法的功能。此外，PowellSnakes的优势在于，始终如一地界定了接受/拒绝的门槛，这是频率主义方法所不能容​​忍的。我们在这里介绍这种技术的第一个实现（版本-I）。目前正在进一步完善这一实施工作，并将于近期出版。该方法在实际模拟普朗克观测中的应用将在即将出版的论文中介绍。

##### URL
[https://arxiv.org/abs/0802.3916](https://arxiv.org/abs/0802.3916)

##### PDF
[https://arxiv.org/pdf/0802.3916](https://arxiv.org/pdf/0802.3916)

