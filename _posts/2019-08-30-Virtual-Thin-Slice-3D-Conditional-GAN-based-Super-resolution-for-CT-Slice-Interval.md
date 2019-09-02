---
layout: post
title: "Virtual Thin Slice: 3D Conditional GAN-based Super-resolution for CT Slice Interval"
date: 2019-08-30 02:01:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN CNN VQA
author: Akira Kudo, Yoshiro Kitamura, Yuanzhong Li, Satoshi Iizuka, Edgar Simo-Serra
mathjax: true
---

* content
{:toc}

##### Abstract
Many CT slice images are stored with large slice intervals to reduce storage size in clinical practice. This leads to low resolution perpendicular to the slice images (\textit{i.e.}, z-axis), which is insufficient for 3D visualization or image analysis. In this paper, we present a novel architecture based on conditional Generative Adversarial Networks (cGANs) with the goal of generating high resolution images of main body parts including head, chest, abdomen and legs. However, GANs are known to have a difficulty with generating a diversity of patterns due to a phenomena known as mode collapse. To overcome the lack of generated pattern variety, we propose to condition the discriminator on the different body parts. Furthermore, our generator networks are extended to be three dimensional fully convolutional neural networks, allowing for the generation of high resolution images from arbitrary fields of view. In our verification tests, we show that the proposed method obtains the best scores by PSNR/SSIM metrics and Visual Turing Test, allowing for accurate reproduction of the principle anatomy in high resolution. We expect that the proposed method contribute to effective utilization of the existing vast amounts of thick CT images stored in hospitals.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11506](http://arxiv.org/abs/1908.11506)

##### PDF
[http://arxiv.org/pdf/1908.11506](http://arxiv.org/pdf/1908.11506)

