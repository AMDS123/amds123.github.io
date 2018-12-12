---
layout: post
title: "Non-local Meets Global: An Integrated Paradigm for Hyperspectral Denoising"
date: 2018-12-11 07:26:07
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Wei He, Quanming Yao, Chao Li, Naoto Yokoya, Qibin Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Non-local low-rank tensor approximation has been developed as a state-of-the-art method for hyperspectral image (HSI) denoising. Unfortunately, with more spectral bands for HSI, while the running time of these methods significantly increases, their denoising performance benefits little. In this paper, we claim that the HSI underlines a global spectral low-rank subspace, and the spectral subspaces of each full band patch groups should underlie this global low-rank subspace. This motivates us to propose a unified spatial-spectral paradigm for HSI denoising. As the new model is hard to optimize, we further propose an efficient algorithm for optimization, which is motivated by alternating minimization. This is done by first learning a low-dimensional projection and the related reduced image from the noisy HSI. Then, the non-local low-rank denoising and iterative regularization are developed to refine the reduced image and projection, respectively. Finally, experiments on synthetic and both real datasets demonstrate the superiority against the other state-of-the-arts HSI denoising methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04243](http://arxiv.org/abs/1812.04243)

##### PDF
[http://arxiv.org/pdf/1812.04243](http://arxiv.org/pdf/1812.04243)

