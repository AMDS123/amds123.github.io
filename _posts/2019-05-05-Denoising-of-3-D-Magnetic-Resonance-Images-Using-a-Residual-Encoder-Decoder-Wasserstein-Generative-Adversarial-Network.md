---
layout: post
title: "Denoising of 3-D Magnetic Resonance Images Using a Residual Encoder-Decoder Wasserstein Generative Adversarial Network"
date: 2019-05-05 03:42:19
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Deep_Learning
author: Maosong Ran, Jinrong Hu, Yang Chen, Hu Chen, Huaiqiang Sun, Jiliu Zhou, Yi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Structure-preserved denoising of 3D magnetic resonance imaging (MRI) images is a critical step in medical image analysis. Over the past few years, many algorithms with impressive performances have been proposed. In this paper, inspired by the idea of deep learning, we introduce an MRI denoising method based on the residual encoder-decoder Wasserstein generative adversarial network (RED-WGAN). Specifically, to explore the structure similarity between neighboring slices, a 3D configuration is utilized as the basic processing unit. Residual autoencoders combined with deconvolution operations are introduced into the generator network. Furthermore, to alleviate the oversmoothing shortcoming of the traditional mean squared error (MSE) loss function, the perceptual similarity, which is implemented by calculating the distances in the feature space extracted by a pretrained VGG-19 network, is incorporated with the MSE and adversarial losses to form the new loss function. Extensive experiments are implemented to assess the performance of the proposed method. The experimental results show that the proposed RED-WGAN achieves performance superior to several state-of-the-art methods in both simulated and real clinical data. In particular, our method demonstrates powerful abilities in both noise suppression and structure preservation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.03941](http://arxiv.org/abs/1808.03941)

##### PDF
[http://arxiv.org/pdf/1808.03941](http://arxiv.org/pdf/1808.03941)

