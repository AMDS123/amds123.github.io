---
layout: post
title: "Accelerated Optimization in the PDE Framework: Formulations for the Active Contour Case"
date: 2017-11-27 18:27:24
categories: arXiv_CV
tags: arXiv_CV Face Optimization Gradient_Descent
author: Anthony Yezzi, Ganesh Sundaramoorthi
mathjax: true
---

* content
{:toc}

##### Abstract
Following the seminal work of Nesterov, accelerated optimization methods have been used to powerfully boost the performance of first-order, gradient-based parameter estimation in scenarios where second-order optimization strategies are either inapplicable or impractical. Not only does accelerated gradient descent converge considerably faster than traditional gradient descent, but it also performs a more robust local search of the parameter space by initially overshooting and then oscillating back as it settles into a final configuration, thereby selecting only local minimizers with a basis of attraction large enough to contain the initial overshoot. This behavior has made accelerated and stochastic gradient search methods particularly popular within the machine learning community. In their recent PNAS 2016 paper, Wibisono, Wilson, and Jordan demonstrate how a broad class of accelerated schemes can be cast in a variational framework formulated around the Bregman divergence, leading to continuum limit ODE's. We show how their formulation may be further extended to infinite dimension manifolds (starting here with the geometric space of curves and surfaces) by substituting the Bregman divergence with inner products on the tangent space and explicitly introducing a distributed mass model which evolves in conjunction with the object of interest during the optimization process. The co-evolving mass model, which is introduced purely for the sake of endowing the optimization with helpful dynamics, also links the resulting class of accelerated PDE based optimization schemes to fluid dynamical formulations of optimal mass transport.

##### Abstract (translated by Google)
在Nesterov的开创性工作之后，在二阶优化策略不适用或者不切实际的情况下，加速优化方法已经被用来强有力地提高一阶梯度参数估计的性能。加速梯度下降不仅比传统的梯度下降收敛得快得多，而且还通过初始超调并且随着其稳定到最终配置而执行更加鲁棒的局部搜索参数空间，从而仅选择具有基础的局部最小值的吸引力足以容纳最初的超调。这种行为使加速和随机梯度搜索方法在机器学习社区中特别受欢迎。威比索诺，威尔逊和约旦最近在其2016年的“2016年PNAS论文”中展示了如何在围绕布雷格曼分歧制定的变化框架中推出一大类加速计划，从而导致连续限制ODE。我们展示了他们的公式如何进一步扩展到无限维流形（从曲线和曲面的几何空间开始），用切向空间上的内积代替Bregman散度，并明确引入一个分布式质量模型，优化过程中感兴趣的对象。共同演化的质量模型，纯粹是为了赋予有益的动力学优化而引入的，也将所得到的基于加速PDE的优化方案与最优质量传输的流体动力学制定联系起来。

##### URL
[https://arxiv.org/abs/1711.09867](https://arxiv.org/abs/1711.09867)

##### PDF
[https://arxiv.org/pdf/1711.09867](https://arxiv.org/pdf/1711.09867)

