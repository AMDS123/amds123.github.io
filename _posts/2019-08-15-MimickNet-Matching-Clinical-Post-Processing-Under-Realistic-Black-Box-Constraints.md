---
layout: post
title: "MimickNet, Matching Clinical Post-Processing Under Realistic Black-Box Constraints"
date: 2019-08-15 22:10:41
categories: arXiv_CV
tags: arXiv_CV Knowledge Deep_Learning
author: Ouwen Huang, Will Long, Nick Bottenus, Gregg E. Trahey, Sina Farsiu, Mark L. Palmeri
mathjax: true
---

* content
{:toc}

##### Abstract
Image post-processing is used in clinical-grade ultrasound scanners to improve image quality (e.g., reduce speckle noise and enhance contrast). These post-processing techniques vary across manufacturers and are generally kept proprietary, which presents a challenge for researchers looking to match current clinical-grade workflows. We introduce a deep learning framework, MimickNet, that transforms raw conventional delay-and-summed (DAS) beams into the approximate post-processed images found on clinical-grade scanners. Training MimickNet only requires post-processed image samples from a scanner of interest without the need for explicit pairing to raw DAS data. This flexibility allows it to hypothetically approximate any manufacturer's post-processing without access to the pre-processed data. MimickNet generates images with an average similarity index measurement (SSIM) of 0.930$\pm$0.0892 on a 300 cineloop test set, and it generalizes to cardiac cineloops outside of our train-test distribution achieving an SSIM of 0.967$\pm$0.002. We also explore the theoretical SSIM achievable by evaluating MimickNet performance when trained under gray-box constraints (i.e., when both pre-processed and post-processed images are available). To our knowledge, this is the first work to establish deep learning models that closely approximate current clinical-grade ultrasound post-processing under realistic black-box constraints where before and after post-processing data is unavailable. MimickNet serves as a clinical post-processing baseline for future works in ultrasound image formation to compare against. To this end, we have made the MimickNet software open source.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05782](https://arxiv.org/abs/1908.05782)

##### PDF
[https://arxiv.org/pdf/1908.05782](https://arxiv.org/pdf/1908.05782)

