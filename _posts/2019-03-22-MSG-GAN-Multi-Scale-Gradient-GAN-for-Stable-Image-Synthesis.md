---
layout: post
title: "MSG-GAN: Multi-Scale Gradient GAN for Stable Image Synthesis"
date: 2019-03-22 19:48:01
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Animesh Karnewar, Oliver Wang, Raghu Sesha Iyengar
mathjax: true
---

* content
{:toc}

##### Abstract
While Generative Adversarial Networks (GANs) have seen huge successes in image synthesis tasks, they are notoriously difficult to use, in part due to instability during training. One commonly accepted reason for this instability is that gradients passing from the discriminator to the generator can quickly become uninformative, due to a learning imbalance during training. In this work, we propose the Multi-Scale Gradient Generative Adversarial Network (MSG-GAN), a simple but effective technique for addressing this problem which allows the flow of gradients from the discriminator to the generator at multiple scales. This technique provides a stable approach for generating synchronized multi-scale images. We present a very intuitive implementation of the mathematical MSG-GAN framework which uses the concatenation operation in the discriminator computations. We empirically validate the effect of our MSG-GAN approach through experiments on the CIFAR10 and Oxford102 flowers datasets and compare it with other relevant techniques which perform multi-scale image synthesis. In addition, we also provide details of our experiment on CelebA-HQ dataset for synthesizing 1024 x 1024 high resolution images.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.06048](https://arxiv.org/abs/1903.06048)

##### PDF
[https://arxiv.org/pdf/1903.06048](https://arxiv.org/pdf/1903.06048)

