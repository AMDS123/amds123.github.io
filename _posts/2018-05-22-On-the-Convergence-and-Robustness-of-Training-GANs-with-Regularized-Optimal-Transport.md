---
layout: post
title: "On the Convergence and Robustness of Training GANs with Regularized Optimal Transport"
date: 2018-05-22 05:11:47
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Maziar Sanjabi, Jimmy Ba, Meisam Razaviyayn, Jason D. Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) are one of the most practical methods for learning data distributions. A popular GAN formulation is based on the use of Wasserstein distance as a metric between probability distributions. Unfortunately, minimizing the Wasserstein distance between the data distribution and the generative model distribution is a computationally challenging problem as its objective is non-convex, non-smooth, and even hard to compute. In this work, we show that obtaining gradient information of the smoothed Wasserstein GAN formulation, which is based on regularized Optimal Transport (OT), is computationally effortless and hence one can apply first order optimization methods to minimize this objective. Consequently, we establish theoretical convergence guarantee to stationarity for a proposed class of GAN optimization algorithms. Unlike the original non-smooth formulation, our algorithm only requires solving the discriminator to approximate optimality. We apply our method to learning MNIST digits as well as CIFAR-10images. Our experiments show that our method is computationally efficient and generates images comparable to the state of the art algorithms given the same architecture and computational power.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.08249](https://arxiv.org/abs/1802.08249)

##### PDF
[https://arxiv.org/pdf/1802.08249](https://arxiv.org/pdf/1802.08249)

