---
layout: post
title: "Generative Imaging and Image Processing via Generative Encoder"
date: 2019-05-23 19:11:00
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN CNN Optimization
author: Lin Chen, Haizhao Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel generative encoder (GE) model for generative imaging and image processing with applications in compressed sensing and imaging, image compression, denoising, inpainting, deblurring, and super-resolution. The GE model consists of a pre-training phase and a solving phase. In the pre-training phase, we separately train two deep neural networks: a generative adversarial network (GAN) with a generator $\G$ that captures the data distribution of a given image set, and an auto-encoder (AE) network with an encoder $\EN$ that compresses images following the estimated distribution by GAN. In the solving phase, given a noisy image $x=\mathcal{P}(x^*)$, where $x^*$ is the target unknown image, $\mathcal{P}$ is an operator adding an addictive, or multiplicative, or convolutional noise, or equivalently given such an image $x$ in the compressed domain, i.e., given $m=\EN(x)$, we solve the optimization problem 
 \[ 
 z^*=\underset{z}{\mathrm{argmin}} \|\EN(\G(z))-m\|_2^2+\lambda\|z\|_2^2 
 \] to recover the image $x^*$ in a generative way via $\hat{x}:=\G(z^*)\approx x^*$, where $\lambda&gt;0$ is a hyperparameter. The GE model unifies the generative capacity of GANs and the stability of AEs in an optimization framework above instead of stacking GANs and AEs into a single network or combining their loss functions into one as in existing literature. Numerical experiments show that the proposed model outperforms several state-of-the-art algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13300](http://arxiv.org/abs/1905.13300)

##### PDF
[http://arxiv.org/pdf/1905.13300](http://arxiv.org/pdf/1905.13300)

