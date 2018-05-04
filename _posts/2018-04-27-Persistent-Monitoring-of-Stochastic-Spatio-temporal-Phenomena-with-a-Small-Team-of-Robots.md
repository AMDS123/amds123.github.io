---
layout: post
title: "Persistent Monitoring of Stochastic Spatio-temporal Phenomena with a Small Team of Robots"
date: 2018-04-27 14:55:38
categories: arXiv_AI
tags: arXiv_AI
author: Sahil Garg, Nora Ayanian
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a solution for persistent monitoring of real-world stochastic phenomena, where the underlying covariance structure changes sharply across time, using a small number of mobile robot sensors. We propose an adaptive solution for the problem where stochastic real-world dynamics are modeled as a Gaussian Process (GP). The belief on the underlying covariance structure is learned from recently observed dynamics as a Gaussian Mixture (GM) in the low-dimensional hyper-parameters space of the GP and adapted across time using Sequential Monte Carlo methods. Each robot samples a belief point from the GM and locally optimizes a set of informative regions by greedy maximization of the submodular entropy function. The key contributions of this paper are threefold: adapting the belief on the covariance using Markov Chain Monte Carlo (MCMC) sampling such that particles survive even under sharp covariance changes across time; exploiting the belief to transform the problem of entropy maximization into a decentralized one; and developing an approximation algorithm to maximize entropy on a set of informative regions in the continuous space. We illustrate the application of the proposed solution through extensive simulations using an artificial dataset and multiple real datasets from fixed sensor deployments, and compare it to three competing state-of-the-art approaches.

##### Abstract (translated by Google)
本文提出了一种解决方案，通过使用少量移动机器人传感器，持续监测实际随机现象，其中基础协方差结构随时间急剧变化。我们针对随机现实世界动力学被建模为高斯过程（GP）的问题提出了自适应解决方案。对于基础协方差结构的信念是从最近观察到的动力学中学习到的，作为GP的低维超参数空间中的高斯混合（GM）并且使用顺序蒙特卡罗方法随时间调整。每个机器人从GM中采样信念点，并通过贪婪最大化子模块熵函数来局部优化一组信息区域。本文的主要贡献有三个：使用马尔可夫链蒙特卡罗（MCMC）抽样调整对协方差的信念，使得即使在随时间变化的尖锐协方差变化下，粒子仍能存活;利用信念将熵最大化问题转化为分散化问题;以及开发一种近似算法来最大化连续空间中一组信息区域的熵。我们通过使用人造数据集和来自固定传感器部署的多个实际数据集进行大量模拟来说明所提出的解决方案的应用，并将其与三种竞争的最先进方法进行比较。

##### URL
[https://arxiv.org/abs/1804.10544](https://arxiv.org/abs/1804.10544)

##### PDF
[https://arxiv.org/pdf/1804.10544](https://arxiv.org/pdf/1804.10544)

