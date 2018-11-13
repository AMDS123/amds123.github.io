---
layout: post
title: "An Interpretable Generative Model for Handwritten Digit Image Synthesis"
date: 2018-11-11 23:37:07
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Yao Zhu, Saksham Suri, Pranav Kulkarni, Yueru Chen, Jiali Duan, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
An interpretable generative model for handwritten digits synthesis is proposed in this work. Modern image generative models, such as Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs), are trained by backpropagation (BP). The training process is complex and the underlying mechanism is difficult to explain. We propose an interpretable multi-stage PCA method to achieve the same goal and use handwritten digit images synthesis as an illustrative example. First, we derive principal-component-analysis-based (PCA-based) transform kernels at each stage based on the covariance of its inputs. This results in a sequence of transforms that convert input images of correlated pixels to spectral vectors of uncorrelated components. In other words, it is a whitening process. Then, we can synthesize an image based on random vectors and multi-stage transform kernels through a coloring process. The generative model is a feedforward (FF) design since no BP is used in model parameter determination. Its design complexity is significantly lower, and the whole design process is explainable. Finally, we design an FF generative model using the MNIST dataset, compare synthesis results with those obtained by state-of-the-art GAN and VAE methods, and show that the proposed generative model achieves comparable performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04507](http://arxiv.org/abs/1811.04507)

##### PDF
[http://arxiv.org/pdf/1811.04507](http://arxiv.org/pdf/1811.04507)

