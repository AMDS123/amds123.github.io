---
layout: post
title: "Multi-View Stereo by Temporal Nonparametric Fusion"
date: 2019-04-12 20:13:23
categories: arXiv_CV
tags: arXiv_CV Inference
author: Yuxin Hou, Juho Kannala, Arno Solin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel idea for depth estimation from unstructured multi-view image-pose pairs, where the model has capability to leverage information from previous latent-space encodings of the scene. This model uses pairs of images and poses, which are passed through an encoder-decoder model for disparity estimation. The novelty lies in soft-constraining the bottleneck layer by a nonparametric Gaussian process prior. We propose a pose-kernel structure that encourages similar poses to have resembling latent spaces. The flexibility of the Gaussian process (GP) prior provides adapting memory for fusing information from previous views. We train the encoder-decoder and the GP hyperparameters jointly end-to-end. In addition to a batch method, we derive a lightweight estimation scheme that circumvents standard pitfalls in scaling Gaussian process inference, and demonstrate how our scheme can run in real-time on smart devices.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06397](http://arxiv.org/abs/1904.06397)

##### PDF
[http://arxiv.org/pdf/1904.06397](http://arxiv.org/pdf/1904.06397)

