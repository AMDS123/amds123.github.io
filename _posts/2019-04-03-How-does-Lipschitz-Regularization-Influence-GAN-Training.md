---
layout: post
title: "How does Lipschitz Regularization Influence GAN Training?"
date: 2019-04-03 14:00:53
categories: arXiv_CV
tags: arXiv_CV Regularization GAN
author: Yipeng Qin, Niloy Mitra, Peter Wonka
mathjax: true
---

* content
{:toc}

##### Abstract
Lipschitz regularization has shown great success in stabilizing GAN training. Despite the recent algorithmic progress (e.g., weight clipping [2], gradient penalty [5], spectral normalization [18]), the exact reason of its effectiveness is still not well understood. The common belief is that Lipschitz regularization works by keeping the weights of the discriminator network small and thereby bounding the neural network gradients. In this work, we discover an even more important function of Lipschitz regularization. It restricts the domain, range, and interval of attainable gradient values of loss functions, thereby preventing the backpropagation of vanishing or exploding gradients. By introducing the concept of domain scaling, we can decouple the effect of Lipschitz regularization on the discriminator network and the loss function. This enables us to show that discriminator networks with larger weights also perform well as long as the domain of the loss function is scaled down. Empirically, we verify our proposition on the MNIST, CIFAR10 and CelebA datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09567](http://arxiv.org/abs/1811.09567)

##### PDF
[http://arxiv.org/pdf/1811.09567](http://arxiv.org/pdf/1811.09567)

