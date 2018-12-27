---
layout: post
title: "Improving MMD-GAN Training with Repulsive Loss Function"
date: 2018-12-24 13:23:18
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Wei Wang, Yuan Sun, Saman Halgamuge
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial nets (GANs) are widely used to learn the data sampling process and their performance may heavily depend on the loss functions, given a limited computational budget. This study revisits MMD-GAN that uses the maximum mean discrepancy (MMD) as the loss function for GAN and makes two contributions. First, we argue that the existing MMD loss function may discourage the learning of fine details in data as it attempts to contract the discriminator outputs of real data. To address this issue, we propose a repulsive loss function to actively learn the difference among the real data by simply rearranging the terms in MMD. Second, inspired by the hinge loss, we propose a bounded Gaussian kernel to stabilize the training of MMD-GAN with the repulsive loss function. The proposed methods are applied to the unsupervised image generation tasks on CIFAR-10, STL-10, CelebA, and LSUN bedroom datasets. Results show that the repulsive loss function significantly improves over the MMD loss at no additional computational cost and outperforms other representative loss functions. The proposed methods achieve an FID score of 16.21 on the CIFAR-10 dataset using a single DCGAN network and spectral normalization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09916](http://arxiv.org/abs/1812.09916)

##### PDF
[http://arxiv.org/pdf/1812.09916](http://arxiv.org/pdf/1812.09916)

