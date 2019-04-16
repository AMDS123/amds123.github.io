---
layout: post
title: "BAGAN: Data Augmentation with Balancing GAN"
date: 2018-06-05 08:07:30
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Image_Classification Classification
author: Giovanni Mariani, Florian Scheidegger, Roxana Istrate, Costas Bekas, Cristiano Malossi
mathjax: true
---

* content
{:toc}

##### Abstract
Image classification datasets are often imbalanced, characteristic that negatively affects the accuracy of deep-learning classifiers. In this work we propose balancing GAN (BAGAN) as an augmentation tool to restore balance in imbalanced datasets. This is challenging because the few minority-class images may not be enough to train a GAN. We overcome this issue by including during the adversarial training all available images of majority and minority classes. The generative model learns useful features from majority classes and uses these to generate images for minority classes. We apply class conditioning in the latent space to drive the generation process towards a target class. The generator in the GAN is initialized with the encoder module of an autoencoder that enables us to learn an accurate class-conditioning in the latent space. We compare the proposed methodology with state-of-the-art GANs and demonstrate that BAGAN generates images of superior quality when trained with an imbalanced dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.09655](https://arxiv.org/abs/1803.09655)

##### PDF
[https://arxiv.org/pdf/1803.09655](https://arxiv.org/pdf/1803.09655)

