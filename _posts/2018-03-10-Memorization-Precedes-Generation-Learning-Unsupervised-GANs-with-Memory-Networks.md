---
layout: post
title: "Memorization Precedes Generation: Learning Unsupervised GANs with Memory Networks"
date: 2018-03-10 02:47:12
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization Memory_Networks
author: Youngjin Kim, Minjung Kim, Gunhee Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approach to address two issues that commonly occur during training of unsupervised GANs. First, since GANs use only a continuous latent distribution to embed multiple classes or clusters of data, they often do not correctly handle the structural discontinuity between disparate classes in a latent space. Second, discriminators of GANs easily forget about past generated samples by generators, incurring instability during adversarial training. We argue that these two infamous problems of unsupervised GAN training can be largely alleviated by a learnable memory network to which both generators and discriminators can access. Generators can effectively learn representation of training samples to understand underlying cluster distributions of data, which ease the structure discontinuity problem. At the same time, discriminators can better memorize clusters of previously generated samples, which mitigate the forgetting problem. We propose a novel end-to-end GAN model named memoryGAN, which involves a memory network that is unsupervisedly trainable and integrable to many existing GAN models. With evaluations on multiple datasets such as Fashion-MNIST, CelebA, CIFAR10, and Chairs, we show that our model is probabilistically interpretable, and generates realistic image samples of high visual fidelity. The memoryGAN also achieves the state-of-the-art inception scores over unsupervised GAN models on the CIFAR10 dataset, without any optimization tricks and weaker divergences.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.01500](https://arxiv.org/abs/1803.01500)

##### PDF
[https://arxiv.org/pdf/1803.01500](https://arxiv.org/pdf/1803.01500)

