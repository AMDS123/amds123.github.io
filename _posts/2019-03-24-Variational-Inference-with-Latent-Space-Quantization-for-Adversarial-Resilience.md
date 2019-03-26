---
layout: post
title: "Variational Inference with Latent Space Quantization for Adversarial Resilience"
date: 2019-03-24 07:47:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Inference
author: Vinay Kyatham, Prathosh A. P., Deepak Mishra, Tarun Kumar Yadav, Dheeraj Mundhra
mathjax: true
---

* content
{:toc}

##### Abstract
Despite their tremendous success in modelling high-dimensional data manifolds, deep neural networks suffer from the threat of adversarial attacks - Existence of perceptually valid input-like samples obtained through careful perturbations that leads to degradation in the performance of underlying model. Major concerns with existing defense mechanisms include non-generalizability across different attacks, models and large inference time. In this paper, we propose a generalized defense mechanism capitalizing on the expressive power of regularized latent space based generative models. We design an adversarial filter, devoid of access to classifier and adversaries, which makes it usable in tandem with any classifier. The basic idea is to learn a Lipschitz constrained mapping from the data manifold, incorporating adversarial perturbations, to a quantized latent space and re-map it to the true data manifold. Specifically, we simultaneously auto-encode the data manifold and its perturbations implicitly through the perturbations of the regularized and quantized generative latent space, realized using variational inference. We demonstrate the efficacy of the proposed formulation in providing the resilience against multiple attack types (Black and white box) and methods, while being almost real-time. Our experiments show that the proposed method surpasses the state-of-the-art techniques in several cases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09940](http://arxiv.org/abs/1903.09940)

##### PDF
[http://arxiv.org/pdf/1903.09940](http://arxiv.org/pdf/1903.09940)

