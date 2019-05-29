---
layout: post
title: "Invertible generative models for inverse problems: mitigating representation error and dataset bias"
date: 2019-05-28 08:27:53
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial
author: Muhammad Asim, Ali Ahmed, Paul Hand
mathjax: true
---

* content
{:toc}

##### Abstract
Trained generative models have shown remarkable performance as priors for inverse problems in imaging. For example, Generative Adversarial Network priors permit recovery of test images from 5-10x fewer measurements than sparsity priors. Unfortunately, these models may be unable to represent any particular image because of architectural choices, mode collapse, and bias in the training dataset. In this paper, we demonstrate that invertible neural networks, which have zero representation error by design, can be effective natural signal priors at inverse problems such as denoising, compressive sensing, and inpainting. Given a trained generative model, we study the empirical risk formulation of the desired inverse problem under a regularization that promotes high likelihood images, either directly by penalization or algorithmically by initialization. For compressive sensing, invertible priors can yield higher accuracy than sparsity priors across almost all undersampling ratios. For the same accuracy on test images, they can use 10-20x fewer measurements. We demonstrate that invertible priors can yield better reconstructions than sparsity priors for images that have rare features of variation within the biased training set, including out-of-distribution natural images.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11672](https://arxiv.org/abs/1905.11672)

##### PDF
[https://arxiv.org/pdf/1905.11672](https://arxiv.org/pdf/1905.11672)

