---
layout: post
title: "VAE-GANs for Probabilistic Compressive Image Recovery: Uncertainty Analysis"
date: 2019-01-31 06:33:48
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Deep_Learning
author: Vineet Edupuganti, Morteza Mardani, Joseph Cheng, Shreyas Vasanawala, John Pauly
mathjax: true
---

* content
{:toc}

##### Abstract
Recovering high-quality images from limited sensory data is a challenging computer vision problem that has received significant attention in recent years. In particular, solutions based on deep learning, ranging from autoencoders to generative models, have been especially effective. However, comparatively little work has centered on the robustness of such reconstructions in terms of the generation of realistic image artifacts (known as hallucinations) and quantifying uncertainty. In this work, we develop experimental methods to address these concerns, utilizing a variational autoencoder-based generative adversarial network (VAE-GAN) as a probabilistic image recovery algorithm. We evaluate the model's output distribution statistically by exploring the variance, bias, and error associated with generated reconstructions. Furthermore, we perform eigen analysis by examining the Jacobians of outputs with respect to the aliased inputs to more accurately determine which input components can be responsible for deteriorated output quality. Experiments were carried out using a dataset of Knee MRI images, and our results indicate factors such as sampling rate, acquisition model, and loss function impact the model's robustness. We also conclude that a wise choice of hyperparameters can lead to the robust recovery of MRI images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11228](http://arxiv.org/abs/1901.11228)

##### PDF
[http://arxiv.org/pdf/1901.11228](http://arxiv.org/pdf/1901.11228)

