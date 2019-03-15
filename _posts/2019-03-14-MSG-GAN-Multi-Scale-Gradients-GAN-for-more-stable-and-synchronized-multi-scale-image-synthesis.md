---
layout: post
title: "MSG-GAN: Multi-Scale Gradients GAN for more stable and synchronized multi-scale image synthesis"
date: 2019-03-14 14:33:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Animesh Karnewar, Raghu Sesha Iyengar
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Network (GAN) which is widely used for Image synthesis via generative modelling suffers peculiarly from training instability. One of the known reasons for this instability is the passage of uninformative gradients from the Discriminator to the Generator due to learning imbalance between them during training. In this work, we propose Multi-Scale Gradients Generative Adversarial Network (MSG-GAN), a simplistic but effective technique for addressing this problem; by allowing the flow of gradients from the Discriminator to the Generator at multiple scales. This results in the Generator acquiring the ability to synthesize synchronized images at multiple resolutions simultaneously. We also highlight a suite of techniques that together buttress the stability of training without excessive hyperparameter tuning. Our MSG-GAN technique is a generic mathematical framework which has multiple instantiations. We present an intuitive form of this technique which uses the concatenation operation in the Discriminator computations and empirically validate it through experiments on the CelebA-HQ, CIFAR10 and Oxford102 flowers datasets and by comparing it with some of the current state-of-the-art techniques.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06048](http://arxiv.org/abs/1903.06048)

##### PDF
[http://arxiv.org/pdf/1903.06048](http://arxiv.org/pdf/1903.06048)

