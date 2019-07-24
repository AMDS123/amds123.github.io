---
layout: post
title: "Adaptive Regularization via Residual Smoothing in Deep Learning Optimization"
date: 2019-07-23 08:28:09
categories: arXiv_AI
tags: arXiv_AI Regularization Image_Classification Optimization Classification Deep_Learning
author: Junghee Cho, Junseok Kwon, Byung-Woo Hong
mathjax: true
---

* content
{:toc}

##### Abstract
We present an adaptive regularization algorithm that can be effectively applied to the optimization problem in deep learning framework. Our regularization algorithm aims to take into account the fitness of data to the current state of model in the determination of regularity to achieve better generalization. The degree of regularization at each element in the target space of the neural network architecture is determined based on the residual at each optimization iteration in an adaptive way. Our adaptive regularization algorithm is designed to apply a diffusion process driven by the heat equation with spatially varying diffusivity depending on the probability density function following a certain distribution of residual. Our data-driven regularity is imposed by adaptively smoothing a simplified objective function in which the explicit regularization term is omitted in an alternating manner between the evaluation of residual and the determination of the degree of its regularity. The effectiveness of our algorithm is empirically demonstrated by the numerical experiments in the application of image classification problems, indicating that our algorithm outperforms other commonly used optimization algorithms in terms of generalization using popular deep learning models and benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09750](http://arxiv.org/abs/1907.09750)

##### PDF
[http://arxiv.org/pdf/1907.09750](http://arxiv.org/pdf/1907.09750)

