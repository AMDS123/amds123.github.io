---
layout: post
title: "A Bayesian Perspective on the Deep Image Prior"
date: 2019-04-16 04:39:29
categories: arXiv_CV
tags: arXiv_CV CNN Inference Gradient_Descent
author: Zezhou Cheng, Matheus Gadelha, Subhransu Maji, Daniel Sheldon
mathjax: true
---

* content
{:toc}

##### Abstract
The deep image prior was recently introduced as a prior for natural images. It represents images as the output of a convolutional network with random inputs. For "inference", gradient descent is performed to adjust network parameters to make the output match observations. This approach yields good performance on a range of image reconstruction tasks. We show that the deep image prior is asymptotically equivalent to a stationary Gaussian process prior in the limit as the number of channels in each layer of the network goes to infinity, and derive the corresponding kernel. This informs a Bayesian approach to inference. We show that by conducting posterior inference using stochastic gradient Langevin we avoid the need for early stopping, which is a drawback of the current approach, and improve results for denoising and impainting tasks. We illustrate these intuitions on a number of 1D and 2D signal reconstruction tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07457](http://arxiv.org/abs/1904.07457)

##### PDF
[http://arxiv.org/pdf/1904.07457](http://arxiv.org/pdf/1904.07457)

