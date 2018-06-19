---
layout: post
title: "The Information Autoencoding Family: A Lagrangian Perspective on Latent Variable Generative Models"
date: 2018-06-18 06:51:28
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Optimization Inference
author: Shengjia Zhao, Jiaming Song, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
A variety of learning objectives have been proposed for training latent variable generative models. We show that many of them, including InfoGAN, ALI/BiGAN, ALICE, CycleGAN, beta-VAE, adversarial autoencoders, AVB, AS-VAE and InfoVAE, are Lagrangian duals of the same primal optimization problem, corresponding to different settings of the Lagrange multipliers. The primal problem optimizes the mutual information between latent and visible variables, subject to the constraints of accurately modeling the data distribution and performing correct amortized inference. Based on this observation, we provide an exhaustive characterization of the statistical and computational trade-offs made by all the training objectives in this class of Lagrangian duals. Next, we propose a dual optimization method where we optimize model parameters as well as the Lagrange multipliers. This method achieves Pareto near-optimal solutions in terms of optimizing information and satisfying the consistency constraints.

##### Abstract (translated by Google)
已经提出了多种学习目标来训练潜在变量生成模型。我们展示了其中包括InfoGAN，ALI / BiGAN，ALICE，CycleGAN，beta-VAE，敌对自动编码器，AVB，AS-VAE和InfoVAE在内的很多都是相同原始优化问题的拉格朗日对偶，对应于拉格朗日的不同设置乘数。原始问题优化潜在变量和可见变量之间的互信息，受限于准确建模数据分布和执行正确的摊销推理。基于这一观察结果，我们详细描述了拉格朗日对偶中所有训练目标的统计和计算折衷。接下来，我们提出一种双优化方法，其中我们优化模型参数以及拉格朗日乘子。该方法在优化信息和满足一致性约束方面实现了帕累托近似最优解。

##### URL
[http://arxiv.org/abs/1806.06514](http://arxiv.org/abs/1806.06514)

##### PDF
[http://arxiv.org/pdf/1806.06514](http://arxiv.org/pdf/1806.06514)

