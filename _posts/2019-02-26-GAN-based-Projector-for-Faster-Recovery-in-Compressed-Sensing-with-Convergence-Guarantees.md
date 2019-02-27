---
layout: post
title: "GAN-based Projector for Faster Recovery in Compressed Sensing with Convergence Guarantees"
date: 2019-02-26 01:50:21
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Gradient_Descent
author: Ankit Raj, Yuqi Li, Yoram Bresler
mathjax: true
---

* content
{:toc}

##### Abstract
A Generative Adversarial Network (GAN) with generator $G$ trained to model the prior of images has been shown to perform better than sparsity-based regularizers in ill-posed inverse problems. In this work, we propose a new method of deploying a GAN-based prior to solve linear inverse problems using projected gradient descent (PGD). Our method learns a network-based projector for use in the PGD algorithm, eliminating the need for expensive computation of the Jacobian of $G$. Experiments show that our approach provides a speed-up of $30\text{-}40\times$ over earlier GAN-based recovery methods for similar accuracy in compressed sensing. Our main theoretical result is that if the measurement matrix is moderately conditioned for range($G$) and the projector is $\delta$-approximate, then the algorithm is guaranteed to reach $O(\delta)$ reconstruction error in $O(log(1/\delta))$ steps in the low noise regime. Additionally, we propose a fast method to design such measurement matrices for a given $G$. Extensive experiments demonstrate the efficacy of this method by requiring $5\text{-}10\times$ fewer measurements than random Gaussian measurement matrices for comparable recovery performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1902.09698](https://arxiv.org/abs/1902.09698)

##### PDF
[https://arxiv.org/pdf/1902.09698](https://arxiv.org/pdf/1902.09698)

