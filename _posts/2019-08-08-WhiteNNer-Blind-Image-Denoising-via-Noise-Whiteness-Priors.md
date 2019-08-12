---
layout: post
title: "WhiteNNer-Blind Image Denoising via Noise Whiteness Priors"
date: 2019-08-08 19:00:17
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Relation
author: Saeed Izadi, Zahra Mirikharaji, Mengliu Zhao, Ghassan Hamarneh
mathjax: true
---

* content
{:toc}

##### Abstract
The accuracy of medical imaging-based diagnostics is directly impacted by the quality of the collected images. A passive approach to improve image quality is one that lags behind improvements in imaging hardware, awaiting better sensor technology of acquisition devices. An alternative, active strategy is to utilize prior knowledge of the imaging system to directly post-process and improve the acquired images. Traditionally, priors about the image properties are taken into account to restrict the solution space. However, few techniques exploit the prior about the noise properties. In this paper, we propose a neural network-based model for disentangling the signal and noise components of an input noisy image, without the need for any ground truth training data. We design a unified loss function that encodes priors about signal as well as noise estimate in the form of regularization terms. Specifically, by using total variation and piecewise constancy priors along with noise whiteness priors such as auto-correlation and stationary losses, our network learns to decouple an input noisy image into the underlying signal and noise components. We compare our proposed method to Noise2Noise and Noise2Self, as well as non-local mean and BM3D, on three public confocal laser endomicroscopy datasets. Experimental results demonstrate the superiority of our network compared to state-of-the-art in terms of PSNR and SSIM.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03238](https://arxiv.org/abs/1908.03238)

##### PDF
[https://arxiv.org/pdf/1908.03238](https://arxiv.org/pdf/1908.03238)

