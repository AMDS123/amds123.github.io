---
layout: post
title: "Single Image Super-resolution via Dense Blended Attention Generative Adversarial Network for Clinical Diagnosis"
date: 2019-06-15 15:13:41
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution Attention GAN Deep_Learning
author: Kewen Liu, Yuan Ma, Hongxia Xiong, Zejun Yan, Zhijun Zhou, Chaoyang Liu, Panpan Fang, Xiaojun Li, Yalei Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In clinical diagnosis, doctors are able to see biological tissues and early lesions more clearly with the assistance of high-resolution(HR) medical images, which is of vital significance for improving diagnosis accuracy. In order to address the issue that medical images would suffer from severe blurring caused by lack of high-frequency details, this paper develops a novel image super-resolution(SR) algorithm called SR-DBAN via dense neural network and blended attention mechanism. Specifically, a novel blended attention block is proposed and introduced to dense neural network(DenseNet), so that the neural network can concentrate more attention to the regions and channels with sufficient high-frequency details adaptively. In the framework of SR-DBAN, batch normalization layers in the original DenseNet are removed to avoid loss of high-frequency texture details, final HR images are obtained by deconvolution at the very end of the network. Furthermore, inspired by the impressive performance of generative adversarial network, this paper develops a novel image SR algorithm called SR-DBAGAN via dense blended attention generative adversarial network. SR-DBAGAN consists a generator and a discriminator, the generator uses our proposed SR-DBAN to generate HR images and try to fool the discriminator while the discriminator is designed based on Wasserstein GAN(WGAN) to discriminate. We deployed our algorithms on blurry prostate MRI images, and experimental results showed that our proposed algorithms have generated considerable sharpness and texture details and have a significant improvement on the peak signal-to-noise ratio(PSNR) and structural similarity index(SSIM), respectively, compared with mainstream interpolation-based and deep learning-based image SR algorithms, which fully proves the effectiveness and superiority of our proposed algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06575](http://arxiv.org/abs/1906.06575)

##### PDF
[http://arxiv.org/pdf/1906.06575](http://arxiv.org/pdf/1906.06575)

