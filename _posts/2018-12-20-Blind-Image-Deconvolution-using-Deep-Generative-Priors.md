---
layout: post
title: "Blind Image Deconvolution using Deep Generative Priors"
date: 2018-12-20 18:29:07
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Gradient_Descent
author: Muhammad Asim, Fahad Shamshad, Ali Ahmed
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel approach to regularize the \textit{ill-posed} and \textit{non-linear} blind image deconvolution (blind deblurring) using deep generative networks. We employ two separate deep generative models --- one trained to produce sharp images while the other trained to generate blur kernels from lower-dimensional parameters. To deblur, we propose an alternating gradient descent scheme operating in the latent lower-dimensional space of each of the pretrained generative models. Our experiments show promising deblurring results on images even under large blurs, and heavy noise. The deblurring performance depends on how well the range of the generator spans the image class. To improve the performance on rich image datasets such as face images not \textit{well learned} by the generative networks, we present a modification of the proposed scheme that governs the deblurring process under both generative, and classical priors. We go on further to show that including a generative prior is, in general, a good idea in image deblurring on even richer images e.g. arbitrary natural images, by demonstrating that untrained convolutional generative networks can act as good image priors based on their structure alone. Our novel proposed approach of using generative networks as priors is in stark contrast to the conventional end-to-end approaches, where a deep neural network is trained on blurred input, and the corresponding sharp output images, while completely ignoring the knowledge of the underlying forward map (convolution operator) in image blurring.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.04073](http://arxiv.org/abs/1802.04073)

##### PDF
[http://arxiv.org/pdf/1802.04073](http://arxiv.org/pdf/1802.04073)

