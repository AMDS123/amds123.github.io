---
layout: post
title: "Parallel Multiscale Autoregressive Density Estimation"
date: 2017-03-10 12:58:23
categories: arXiv_CV
tags: arXiv_CV Inference
author: Scott Reed, Aäron van den Oord, Nal Kalchbrenner, Sergio Gómez Colmenarejo, Ziyu Wang, Dan Belov, Nando de Freitas
mathjax: true
---

* content
{:toc}

##### Abstract
PixelCNN achieves state-of-the-art results in density estimation for natural images. Although training is fast, inference is costly, requiring one network evaluation per pixel; O(N) for N pixels. This can be sped up by caching activations, but still involves generating each pixel sequentially. In this work, we propose a parallelized PixelCNN that allows more efficient inference by modeling certain pixel groups as conditionally independent. Our new PixelCNN model achieves competitive density estimation and orders of magnitude speedup - O(log N) sampling instead of O(N) - enabling the practical generation of 512x512 images. We evaluate the model on class-conditional image generation, text-to-image synthesis, and action-conditional video generation, showing that our model achieves the best results among non-pixel-autoregressive density models that allow efficient sampling.

##### Abstract (translated by Google)
PixelCNN在自然图像的密度估计方面达到了最先进的效果。尽管训练速度快，推理成本高，每个像素需要一个网络评估; O（N）为N个像素。这可以通过缓存激活来加速，但仍涉及依次生成每个像素。在这项工作中，我们提出了一个并行化的PixelCNN，它允许通过对某些像素组建模作为条件独立来进行更高效的推理。我们的新PixelCNN模型实现了竞争密度估计和数量级的加速 -  O（log N）采样，而不是O（N） - 实现了512x512图像的实际生成。我们对类条件图像生成，文本到图像合成和动作条件视频生成评估模型，表明我们的模型在允许有效采样的非像素自回归密度模型中取得了最好的结果。

##### URL
[https://arxiv.org/abs/1703.03664](https://arxiv.org/abs/1703.03664)

##### PDF
[https://arxiv.org/pdf/1703.03664](https://arxiv.org/pdf/1703.03664)

