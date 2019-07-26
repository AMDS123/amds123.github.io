---
layout: post
title: "Y-Autoencoders: disentangling latent representations via sequential-encoding"
date: 2019-07-25 10:28:15
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Massimiliano Patacchiola, Patrick Fox-Roberts, Edward Rosten
mathjax: true
---

* content
{:toc}

##### Abstract
In the last few years there have been important advancements in generative models with the two dominant approaches being Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs). However, standard Autoencoders (AEs) and closely related structures have remained popular because they are easy to train and adapt to different tasks. An interesting question is if we can achieve state-of-the-art performance with AEs while retaining their good properties. We propose an answer to this question by introducing a new model called Y-Autoencoder (Y-AE). The structure and training procedure of a Y-AE enclose a representation into an implicit and an explicit part. The implicit part is similar to the output of an autoencoder and the explicit part is strongly correlated with labels in the training set. The two parts are separated in the latent space by splitting the output of the encoder into two paths (forming a Y shape) before decoding and re-encoding. We then impose a number of losses, such as reconstruction loss, and a loss on dependence between the implicit and explicit parts. Additionally, the projection in the explicit manifold is monitored by a predictor, that is embedded in the encoder and trained end-to-end with no adversarial losses. We provide significant experimental results on various domains, such as separation of style and content, image-to-image translation, and inverse graphics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10949](http://arxiv.org/abs/1907.10949)

##### PDF
[http://arxiv.org/pdf/1907.10949](http://arxiv.org/pdf/1907.10949)

