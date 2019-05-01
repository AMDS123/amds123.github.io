---
layout: post
title: "CT-To-MR Conditional Generative Adversarial Networks for Ischemic Stroke Lesion Segmentation"
date: 2019-04-30 14:42:53
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Quantitative
author: Jonathan Rubin, S. Mazdak Abulnaga
mathjax: true
---

* content
{:toc}

##### Abstract
Infarcted brain tissue resulting from acute stroke readily shows up as hyperintense regions within diffusion-weighted magnetic resonance imaging (DWI). It has also been proposed that computed tomography perfusion (CTP) could alternatively be used to triage stroke patients, given improvements in speed and availability, as well as reduced cost. However, CTP has a lower signal to noise ratio compared to MR. In this work, we investigate whether a conditional mapping can be learned by a generative adversarial network to map CTP inputs to generated MR DWI that more clearly delineates hyperintense regions due to ischemic stroke. We detail the architectures of the generator and discriminator and describe the training process used to perform image-to-image translation from multi-modal CT perfusion maps to diffusion weighted MR outputs. We evaluate the results both qualitatively by visual comparison of generated MR to ground truth, as well as quantitatively by training fully convolutional neural networks that make use of generated MR data inputs to perform ischemic stroke lesion segmentation. Segmentation networks trained using generated CT-to-MR inputs result in at least some improvement on all metrics used for evaluation, compared with networks that only use CT perfusion input.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.13281](http://arxiv.org/abs/1904.13281)

##### PDF
[http://arxiv.org/pdf/1904.13281](http://arxiv.org/pdf/1904.13281)

