---
layout: post
title: "Real-Time Adaptive Image Compression"
date: 2017-05-16 17:51:07
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial
author: Oren Rippel, Lubomir Bourdev
mathjax: true
---

* content
{:toc}

##### Abstract
We present a machine learning-based approach to lossy image compression which outperforms all existing codecs, while running in real-time. Our algorithm typically produces files 2.5 times smaller than JPEG and JPEG 2000, 2 times smaller than WebP, and 1.7 times smaller than BPG on datasets of generic images across all quality levels. At the same time, our codec is designed to be lightweight and deployable: for example, it can encode or decode the Kodak dataset in around 10ms per image on GPU. Our architecture is an autoencoder featuring pyramidal analysis, an adaptive coding module, and regularization of the expected codelength. We also supplement our approach with adversarial training specialized towards use in a compression setting: this enables us to produce visually pleasing reconstructions for very low bitrates.

##### Abstract (translated by Google)
我们提出了一种基于机器学习的方法来实现有损图像压缩，其优于所有现有的编解码器，而实时运行。我们的算法通常会生成比JPEG和JPEG 2000小2.5倍的文件，比WebP小2倍，比所有质量级别的通用图像数据集上的BPG小1.7倍。与此同时，我们的编解码器被设计为轻量级且可部署的：例如，它可以在GPU上以每个图像约10ms对柯达数据集进行编码或解码。我们的架构是一个自动编码器，具有金字塔分析，自适应编码模块，以及预期码长的正则化。我们还通过针对在压缩设置中使用的对抗训练来补充我们的方法：这使得我们能够以非常低的比特率产生视觉上令人愉快的重建。

##### URL
[https://arxiv.org/abs/1705.05823](https://arxiv.org/abs/1705.05823)

##### PDF
[https://arxiv.org/pdf/1705.05823](https://arxiv.org/pdf/1705.05823)

