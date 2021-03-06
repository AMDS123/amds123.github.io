---
layout: post
title: "Improving GAN with neighbors embedding and gradient matching"
date: 2018-11-04 08:06:59
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Embedding
author: Ngoc-Trung Tran, Tuan-Anh Bui, Ngai-Man Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
We propose two new techniques for training Generative Adversarial Networks (GANs). Our objectives are to alleviate mode collapse in GAN and improve the quality of the generated samples. First, we propose neighbor embedding, a manifold learning-based regularization to explicitly retain local structures of latent samples in the generated samples. This prevents generator from producing nearly identical data samples from different latent samples, and reduces mode collapse. We propose an inverse t-SNE regularizer to achieve this. Second, we propose a new technique, gradient matching, to align the distributions of the generated samples and the real samples. As it is challenging to work with high-dimensional sample distributions, we propose to align these distributions through the scalar discriminator scores. We constrain the difference between the discriminator scores of the real samples and generated ones. We further constrain the difference between the gradients of these discriminator scores. We derive these constraints from Taylor approximations of the discriminator function. We perform experiments to demonstrate that our proposed techniques are computationally simple and easy to be incorporated in existing systems. When Gradient matching and Neighbour embedding are applied together, our GN-GAN achieves outstanding results on 1D/2D synthetic, CIFAR-10 and STL-10 datasets, e.g. FID score of $30.80$ for the STL-10 dataset. Our code is available at: this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.01333](https://arxiv.org/abs/1811.01333)

##### PDF
[https://arxiv.org/pdf/1811.01333](https://arxiv.org/pdf/1811.01333)

