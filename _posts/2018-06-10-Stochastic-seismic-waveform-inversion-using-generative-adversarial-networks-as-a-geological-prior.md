---
layout: post
title: "Stochastic seismic waveform inversion using generative adversarial networks as a geological prior"
date: 2018-06-10 20:38:29
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Lukas Mosser, Olivier Dubrule, Martin J. Blunt
mathjax: true
---

* content
{:toc}

##### Abstract
We present an application of deep generative models in the context of partial-differential equation (PDE) constrained inverse problems. We combine a generative adversarial network (GAN) representing an a priori model that creates subsurface geological structures and their petrophysical properties, with the numerical solution of the PDE governing the propagation of acoustic waves within the earth's interior. We perform Bayesian inversion using an approximate Metropolis-adjusted Langevin algorithm (MALA) to sample from the posterior given seismic observations. Gradients with respect to the model parameters governing the forward problem are obtained by solving the adjoint of the acoustic wave equation. Gradients of the mismatch with respect to the latent variables are obtained by leveraging the differentiable nature of the deep neural network used to represent the generative model. We show that approximate MALA sampling allows efficient Bayesian inversion of model parameters obtained from a prior represented by a deep generative model, obtaining a diverse set of realizations that reflect the observed seismic response.

##### Abstract (translated by Google)
我们介绍了深部生成模型在偏微分方程（PDE）约束反问题中的应用。我们结合了一个代表先验模型的生成对抗网络（GAN），该网络创建地下地质结构及其岩石物理特性，以及控制声波在地球内部传播的PDE的数值解。我们使用近似的Metropolis调整的Langevin算法（MALA）进行贝叶斯反演，以从后验给定的地震观测值中采样。通过求解声波方程的伴随而获得关于控制前向问题的模型参数的梯度。通过利用用于表示生成模型的深层神经网络的可微性质来获得关于潜变量的失配梯度。我们表明，近似MALA采样允许高效的贝叶斯反演模型参数从先前的深层生成模型获得，获得反映观测到的地震响应的多种实现。

##### URL
[http://arxiv.org/abs/1806.03720](http://arxiv.org/abs/1806.03720)

##### PDF
[http://arxiv.org/pdf/1806.03720](http://arxiv.org/pdf/1806.03720)

