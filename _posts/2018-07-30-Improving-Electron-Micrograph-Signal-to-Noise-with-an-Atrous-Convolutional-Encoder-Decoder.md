---
layout: post
title: "Improving Electron Micrograph Signal-to-Noise with an Atrous Convolutional Encoder-Decoder"
date: 2018-07-30 08:48:32
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jeffrey M. Ede
mathjax: true
---

* content
{:toc}

##### Abstract
We present an atrous convolutional encoder-decoder trained to denoise 512$\times$512 crops from electron micrographs. It consists of a modified Xception backbone, atrous convoltional spatial pyramid pooling module and a multi-stage decoder. Our neural network was trained end-to-end to remove Poisson noise applied to low-dose ($\ll$ 300 counts ppx) micrographs created from a new dataset of 17267 2048$\times$2048 high-dose ($&gt;$ 2500 counts ppx) micrographs and then fine-tuned for ordinary doses (200-2500 counts ppx). Its performance is benchmarked against bilateral, non-local means, total variation, wavelet, Wiener and other restoration methods with their default parameters. Our network outperforms their best mean squared error and structural similarity index performances by 24.6% and 9.6% for low doses and by 43.7% and 5.5% for ordinary doses. In both cases, our network's mean squared error has the lowest variance. Source code and links to our new high-quality dataset and trained network have been made publicly available at https://github.com/Jeffrey-Ede/Electron-Micrograph-Denoiser

##### Abstract (translated by Google)
我们提出了一个令人厌恶的卷积编码器 - 解码器，它可以从电子显微照片中去除512美元以上的512美元作物。它由修改的Xception主干，atrous convoltional空间金字塔池模块和多级解码器组成。我们的神经网络端到端训练，以消除应用于低剂量（$ \ ll $ 300计数ppx）显微照片的泊松噪声，该显微照片由17267 2048 $ \倍2048美元高剂量（$＆gt; 2500美元）的新数据集创建计算ppx）显微照片，然后微调普通剂量（200-2500计数ppx）。其性能基于双边，非局部均值，总变差，小波，维纳和其他恢复方法及其默认参数。我们的网络在低剂量时的表现优于最佳均方误差和结构相似性指数表现为24.6％和9.6％，普通剂量表现为43.7％和5.5％。在这两种情况下，我们网络的均方误差具有最低的方差。源代码和我们新的高质量数据集和训练网络的链接已在https://github.com/Jeffrey-Ede/Electron-Micrograph-Denoiser公开发布

##### URL
[http://arxiv.org/abs/1807.11234](http://arxiv.org/abs/1807.11234)

##### PDF
[http://arxiv.org/pdf/1807.11234](http://arxiv.org/pdf/1807.11234)

