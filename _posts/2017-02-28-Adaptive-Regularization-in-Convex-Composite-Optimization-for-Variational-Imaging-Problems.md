---
layout: post
title: "Adaptive Regularization in Convex Composite Optimization for Variational Imaging Problems"
date: 2017-02-28 12:58:18
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Optimization Quantitative
author: Byung-Woo Hong, Ja-Keoung Koo, Hendrik Dirks, Martin Burger
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an adaptive regularization scheme in a variational framework where a convex composite energy functional is optimized. We consider a number of imaging problems including denoising, segmentation and motion estimation, which are considered as optimal solutions of the energy functionals that mainly consist of data fidelity, regularization and a control parameter for their trade-off. We presents an algorithm to determine the relative weight between data fidelity and regularization based on the residual that measures how well the observation fits the model. Our adaptive regularization scheme is designed to locally control the regularization at each pixel based on the assumption that the diversity of the residual of a given imaging model spatially varies. The energy optimization is presented in the alternating direction method of multipliers (ADMM) framework where the adaptive regularization is iteratively applied along with mathematical analysis of the proposed algorithm. We demonstrate the robustness and effectiveness of our adaptive regularization through experimental results presenting that the qualitative and quantitative evaluation results of each imaging task are superior to the results with a constant regularization scheme. The desired properties, robustness and effectiveness, of the regularization parameter selection in a variational framework for imaging problems are achieved by merely replacing the static regularization parameter with our adaptive one.

##### Abstract (translated by Google)
我们提出了一个自适应正则化方案在一个变异的框架，其中凸复合能量功能进行了优化。我们考虑了一些成像问题，包括去噪，分割和运动估计，它们被认为是能量函数的最优解，主要由数据保真度，正则化和控制参数组成。我们提出了一个算法来确定数据保真度和正则化之间的相对权重，基于残差来衡量观测如何符合模型。我们的自适应正则化方案被设计为基于假定给定成像模型的残差在空间上变化的假设来在每个像素处局部地控制正则化。在交错方向的乘法器（ADMM）框架中提出了能量优化，其中自适应正则化被迭代应用，并且对所提出的算法进行数学分析。我们通过实验结果证明了我们自适应正则化的稳健性和有效性，实验结果表明每个成像任务的定性和定量评估结果优于具有恒定正则化方案的结果。通过用我们的自适应参数代替静态正则化参数，实现了用于成像问题的变分框架中的正则化参数选择的所需性质，鲁棒性和有效性。

##### URL
[https://arxiv.org/abs/1609.02356](https://arxiv.org/abs/1609.02356)

##### PDF
[https://arxiv.org/pdf/1609.02356](https://arxiv.org/pdf/1609.02356)

