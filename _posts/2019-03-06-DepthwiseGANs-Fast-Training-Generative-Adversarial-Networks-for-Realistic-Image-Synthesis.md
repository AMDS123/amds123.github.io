---
layout: post
title: "DepthwiseGANs: Fast Training Generative Adversarial Networks for Realistic Image Synthesis"
date: 2019-03-06 07:56:49
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN CNN
author: Mkhuseli Ngxande, Jules-Raymond Tapamo, Michael Burke
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown significant progress in the direction of synthetic data generation using Generative Adversarial Networks (GANs). GANs have been applied in many fields of computer vision including text-to-image conversion, domain transfer, super-resolution, and image-to-video applications. In computer vision, traditional GANs are based on deep convolutional neural networks. However, deep convolutional neural networks can require extensive computational resources because they are based on multiple operations performed by convolutional layers, which can consist of millions of trainable parameters. Training a GAN model can be difficult and it takes a significant amount of time to reach an equilibrium point. In this paper, we investigate the use of depthwise separable convolutions to reduce training time while maintaining data generation performance. Our results show that a DepthwiseGAN architecture can generate realistic images in shorter training periods when compared to a StarGan architecture, but that model capacity still plays a significant role in generative modelling. In addition, we show that depthwise separable convolutions perform best when only applied to the generator. For quality evaluation of generated images, we use the Fr\'echet Inception Distance (FID), which compares the similarity between the generated image distribution and that of the training dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02225](http://arxiv.org/abs/1903.02225)

##### PDF
[http://arxiv.org/pdf/1903.02225](http://arxiv.org/pdf/1903.02225)

