---
layout: post
title: "tempoGAN: A Temporally Coherent, Volumetric GAN for Super-resolution Fluid Flow"
date: 2018-05-28 08:49:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN Inference
author: You Xie, Erik Franz, Mengyu Chu, Nils Thuerey
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a temporally coherent generative model addressing the super-resolution problem for fluid flows. Our work represents a first approach to synthesize four-dimensional physics fields with neural networks. Based on a conditional generative adversarial network that is designed for the inference of three-dimensional volumetric data, our model generates consistent and detailed results by using a novel temporal discriminator, in addition to the commonly used spatial one. Our experiments show that the generator is able to infer more realistic high-resolution details by using additional physical quantities, such as low-resolution velocities or vorticities. Besides improvements in the training process and in the generated outputs, these inputs offer means for artistic control as well. We additionally employ a physics-aware data augmentation step, which is crucial to avoid overfitting and to reduce memory requirements. In this way, our network learns to generate advected quantities with highly detailed, realistic, and temporally coherent features. Our method works instantaneously, using only a single time-step of low-resolution fluid data. We demonstrate the abilities of our method using a variety of complex inputs and applications in two and three dimensions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.09710](https://arxiv.org/abs/1801.09710)

##### PDF
[https://arxiv.org/pdf/1801.09710](https://arxiv.org/pdf/1801.09710)

