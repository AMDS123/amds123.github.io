---
layout: post
title: "Robustness of Conditional GANs to Noisy Labels"
date: 2018-11-08 01:07:17
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Kiran Koshy Thekumparampil, Ashish Khetan, Zinan Lin, Sewoong Oh
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of learning conditional generators from noisy labeled samples, where the labels are corrupted by random noise. A standard training of conditional GANs will not only produce samples with wrong labels, but also generate poor quality samples. We consider two scenarios, depending on whether the noise model is known or not. When the distribution of the noise is known, we introduce a novel architecture which we call Robust Conditional GAN (RCGAN). The main idea is to corrupt the label of the generated sample before feeding to the adversarial discriminator, forcing the generator to produce samples with clean labels. This approach of passing through a matching noisy channel is justified by corresponding multiplicative approximation bounds between the loss of the RCGAN and the distance between the clean real distribution and the generator distribution. This shows that the proposed approach is robust, when used with a carefully chosen discriminator architecture, known as projection discriminator. When the distribution of the noise is not known, we provide an extension of our architecture, which we call RCGAN-U, that learns the noise model simultaneously while training the generator. We show experimentally on MNIST and CIFAR-10 datasets that both the approaches consistently improve upon baseline approaches, and RCGAN-U closely matches the performance of RCGAN.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.03205](https://arxiv.org/abs/1811.03205)

##### PDF
[https://arxiv.org/pdf/1811.03205](https://arxiv.org/pdf/1811.03205)

