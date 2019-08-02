---
layout: post
title: "Defense-VAE: A Fast and Accurate Defense against Adversarial Attacks"
date: 2019-08-01 03:11:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization Prediction
author: Xiang Li, Shihao Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have been enormously successful across a variety of prediction tasks. However, recent research shows that DNNs are particularly vulnerable to adversarial attacks, which poses a serious threat to their applications in security-sensitive systems. In this paper, we propose a simple yet effective defense algorithm Defense-VAE that uses variational autoencoder (VAE) to purge adversarial perturbations from contaminated images. The proposed method is generic and can defend white-box and black-box attacks without the need of retraining the original CNN classifiers, and can further strengthen the defense by retraining CNN or end-to-end finetuning the whole pipeline. In addition, the proposed method is very efficient compared to the optimization-based alternatives, such as Defense-GAN, since no iterative optimization is needed for online prediction. Extensive experiments on MNIST, Fashion-MNIST, CelebA and CIFAR-10 demonstrate the superior defense accuracy of Defense-VAE compared to Defense-GAN, while being 50x faster than the latter. This makes Defense-VAE widely deployable in real-time security-sensitive systems. Our source code can be found at https://github.com/lxuniverse/defense-vae.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06570](http://arxiv.org/abs/1812.06570)

##### PDF
[http://arxiv.org/pdf/1812.06570](http://arxiv.org/pdf/1812.06570)

