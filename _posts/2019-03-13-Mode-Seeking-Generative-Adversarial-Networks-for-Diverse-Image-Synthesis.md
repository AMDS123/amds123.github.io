---
layout: post
title: "Mode Seeking Generative Adversarial Networks for Diverse Image Synthesis"
date: 2019-03-13 17:50:36
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Quantitative
author: Qi Mao, Hsin-Ying Lee, Hung-Yu Tseng, Siwei Ma, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Most conditional generation tasks expect diverse outputs given a single conditional context. However, conditional generative adversarial networks (cGANs) often focus on the prior conditional information and ignore the input noise vectors, which contribute to the output variations. Recent attempts to resolve the mode collapse issue for cGANs are usually task-specific and computationally expensive. In this work, we propose a simple yet effective regularization term to address the mode collapse issue for cGANs. The proposed method explicitly maximizes the ratio of the distance between generated images with respect to the corresponding latent codes, thus encouraging the generators to explore more minor modes during training. This mode seeking regularization term is readily applicable to various conditional generation tasks without imposing training overhead or modifying the original network structures. We validate the proposed algorithm on three conditional image synthesis tasks including categorical generation, image-to-image translation, and text-to-image synthesis with different baseline models. Both qualitative and quantitative results demonstrate the effectiveness of the proposed regularization method for improving diversity without loss of quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05628](http://arxiv.org/abs/1903.05628)

##### PDF
[http://arxiv.org/pdf/1903.05628](http://arxiv.org/pdf/1903.05628)

