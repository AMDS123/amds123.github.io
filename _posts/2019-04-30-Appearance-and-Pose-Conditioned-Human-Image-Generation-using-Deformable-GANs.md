---
layout: post
title: "Appearance and Pose-Conditioned Human Image Generation using Deformable GANs"
date: 2019-04-30 07:35:15
categories: arXiv_CV
tags: arXiv_CV Re-identification Adversarial GAN Person_Re-identification Quantitative
author: Aliaksandr Siarohin, St&#xe9;phane Lathuili&#xe8;re, Enver Sangineto, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the problem of generating person images conditioned on both pose and appearance information. Specifically, given an image xa of a person and a target pose P(xb), extracted from a different image xb, we synthesize a new image of that person in pose P(xb), while preserving the visual details in xa. In order to deal with pixel-to-pixel misalignments caused by the pose differences between P(xa) and P(xb), we introduce deformable skip connections in the generator of our Generative Adversarial Network. Moreover, a nearest-neighbour loss is proposed instead of the common L1 and L2 losses in order to match the details of the generated image with the target image. Quantitative and qualitative results, using common datasets and protocols recently proposed for this task, show that our approach is competitive with respect to the state of the art. Moreover, we conduct an extensive evaluation using off-the-shell person re-identification (Re-ID) systems trained with person-generation based augmented data, which is one of the main important applications for this task. Our experiments show that our Deformable GANs can significantly boost the Re-ID accuracy and are even better than data-augmentation methods specifically trained using Re-ID losses.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00007](http://arxiv.org/abs/1905.00007)

##### PDF
[http://arxiv.org/pdf/1905.00007](http://arxiv.org/pdf/1905.00007)

