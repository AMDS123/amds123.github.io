---
layout: post
title: "Adversarial Spatio-Temporal Learning for Video Deblurring"
date: 2018-03-28 10:25:18
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Kaihao Zhang, Wenhan Luo, Yiran Zhong, Lin Ma, Wei Liu, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Camera shake or target movement often leads to undesired blur effects in videos captured by a hand-held camera. Despite significant efforts being devoted to video-deblur research, two major challenges remain: 1) how to model the spatio-temporal characteristics across both the spatial domain (i.e. image plane) and temporal domain (i.e. neighboring frames), and 2) how to restore sharp image details w.r.t. the conventionally adopted metric of pixel-wise error. In this paper, to address the first challenge, we propose a DeBLuRring Network (DBLRNet) for spatial-temporal learning by applying a modified 3D convolution to both spatial and temporal domains. Our DBLRNet is able to capture jointly spatial and temporal information encoded in neighboring frames, which directly contributes to improved video deblur performance. To tackle the second challenge, we use the developed DBLRNet as a generator in the GAN (generative adversarial network) architecture, and employ a content loss in addition to an adversarial loss for efficient adversarial training. The developed network, which we name as DeBLuRring Generative Adversarial Network (DBLRGAN), is tested on two standard benchmarks and achieves the state-of-the-art performance.

##### Abstract (translated by Google)
相机抖动或目标移动通常会导致手持相机捕捉的视频中出现不希望的模糊效果。尽管在视频去模糊研究方面做出了巨大的努力，但仍然存在两个主要挑战：1）如何跨空间域（即图像平面）和时间域（即相邻帧）对时空特征进行建模，以及2）如何恢复清晰的图像细节常规采用的像素误差度量。在本文中，为了解决第一个挑战，我们通过对空间和时间域应用修改的3D卷积来提出用于空间 - 时间学习的DeBLuRring网络（DBLRNet）。我们的DBLRNet能够共同捕获在相邻帧中编码的空间和时间信息，这直接有助于提高视频去模糊性能。为了解决第二个挑战，我们使用开发的DBLRNet作为GAN（生成对抗网络）体系结构中的生成器，并且除了对抗性损失之外还使用内容损失来进行有效的对抗训练。我们称之为DeBLuRring生成敌对网络（DBLRGAN）的开发网络在两个标准基准测试中进行测试，并达到了最先进的性能。

##### URL
[http://arxiv.org/abs/1804.00533](http://arxiv.org/abs/1804.00533)

##### PDF
[http://arxiv.org/pdf/1804.00533](http://arxiv.org/pdf/1804.00533)

