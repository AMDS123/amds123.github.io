---
layout: post
title: "Learned Spectral Super-Resolution"
date: 2017-03-28 09:17:38
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Silvano Galliani, Charis Lanaras, Dimitrios Marmanis, Emmanuel Baltsavias, Konrad Schindler
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a novel method for blind, single-image spectral super-resolution. While conventional super-resolution aims to increase the spatial resolution of an input image, our goal is to spectrally enhance the input, i.e., generate an image with the same spatial resolution, but a greatly increased number of narrow (hyper-spectral) wave-length bands. Just like the spatial statistics of natural images has rich structure, which one can exploit as prior to predict high-frequency content from a low resolution image, the same is also true in the spectral domain: the materials and lighting conditions of the observed world induce structure in the spectrum of wavelengths observed at a given pixel. Surprisingly, very little work exists that attempts to use this diagnosis and achieve blind spectral super-resolution from single images. We start from the conjecture that, just like in the spatial domain, we can learn the statistics of natural image spectra, and with its help generate finely resolved hyper-spectral images from RGB input. Technically, we follow the current best practice and implement a convolutional neural network (CNN), which is trained to carry out the end-to-end mapping from an entire RGB image to the corresponding hyperspectral image of equal size. We demonstrate spectral super-resolution both for conventional RGB images and for multi-spectral satellite data, outperforming the state-of-the-art.

##### Abstract (translated by Google)
我们描述了一种盲，单图像光谱超分辨率的新方法。虽然传统的超分辨率旨在提高输入图像的空间分辨率，但是我们的目标是在光谱上增强输入，即生成具有相同空间分辨率的图像，但是大量增加窄（高光谱）长度的乐队。就像自然图像的空间统计具有丰富的结构，哪一个可以用来从低分辨率的图像预测高频内容，在频谱域中也是如此：观察世界的材料和光照条件诱导结构在给定像素处观察到的波长谱中。令人惊讶的是，试图使用这种诊断并且从单个图像实现盲光谱超分辨率的工作非常少。我们从猜想开始，就像在空间领域一样，我们可以学习自然图像光谱的统计，并从RGB输入中帮助生成精细解析的高光谱图像。从技术上讲，我们遵循当前的最佳做法，实施一个卷积神经网络（CNN），该网络经过训练，可以从整个RGB图像进行端到端映射到相应大小的相应高光谱图像。我们演示了传统RGB图像和多光谱卫星数据的光谱超分辨率，超越了最先进的技术水平。

##### URL
[https://arxiv.org/abs/1703.09470](https://arxiv.org/abs/1703.09470)

##### PDF
[https://arxiv.org/pdf/1703.09470](https://arxiv.org/pdf/1703.09470)

