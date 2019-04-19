---
layout: post
title: "Reducing Noise in GAN Training with Variance Reduced Extragradient"
date: 2019-04-18 06:02:24
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Optimization
author: Tatjana Chavdarova, Gauthier Gidel, François Fleuret, Simon Lacoste-Julien
mathjax: true
---

* content
{:toc}

##### Abstract
Using large mini-batches when training generative adversarial networks (GANs) has been recently shown to significantly improve the quality of the generated samples. This can be seen as a simple but computationally expensive way of reducing the noise of the gradient estimates. In this paper, we investigate the effect of the noise in this context and show that it can prevent the convergence of standard stochastic game optimization methods, while their respective batch version converges. To address this issue, we propose a variance-reduced version of the stochastic extragradient algorithm (SVRE). We show experimentally that it performs similarly to a batch method, while being computationally cheaper, and show its theoretical convergence, improving upon the best rates proposed in the literature. Experiments on several datasets show that SVRE improves over baselines. Notably, SVRE is the first optimization method for GANs to our knowledge that can produce near state-of-the-art results without using adaptive step-size such as Adam.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.08598](https://arxiv.org/abs/1904.08598)

##### PDF
[https://arxiv.org/pdf/1904.08598](https://arxiv.org/pdf/1904.08598)

