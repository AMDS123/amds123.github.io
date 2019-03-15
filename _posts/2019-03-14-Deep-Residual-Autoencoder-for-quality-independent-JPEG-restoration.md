---
layout: post
title: "Deep Residual Autoencoder for quality independent JPEG restoration"
date: 2019-03-14 16:51:18
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Simone Zini, Simone Bianco, Raimondo Schettini
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a deep residual autoencoder exploiting Residual-in-Residual Dense Blocks (RRDB) to remove artifacts in JPEG compressed images that is independent from the Quality Factor (QF) used. The proposed approach leverages both the learning capacity of deep residual networks and prior knowledge of the JPEG compression pipeline. The proposed model operates in the YCbCr color space and performs JPEG artifact restoration in two phases using two different autoencoders: the first one restores the luma channel exploiting 2D convolutions; the second one, using the restored luma channel as a guide, restores the chroma channels explotining 3D convolutions. Extensive experimental results on three widely used benchmark datasets (i.e. LIVE1, BDS500, and CLASSIC-5) show that our model is able to outperform the state of the art with respect to all the evaluation metrics considered (i.e. PSNR, PSNR-B, and SSIM). This results is remarkable since the approaches in the state of the art use a different set of weights for each compression quality, while the proposed model uses the same weights for all of them, making it applicable to images in the wild where the QF used for compression is unkwnown. Furthermore, the proposed model shows a greater robustness than state-of-the-art methods when applied to compression qualities not seen during training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06117](http://arxiv.org/abs/1903.06117)

##### PDF
[http://arxiv.org/pdf/1903.06117](http://arxiv.org/pdf/1903.06117)

