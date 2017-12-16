---
layout: post
title: "PixelNN: Example-based Image Synthesis"
date: 2017-08-17 16:13:42
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Aayush Bansal, Yaser Sheikh, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple nearest-neighbor (NN) approach that synthesizes high-frequency photorealistic images from an "incomplete" signal such as a low-resolution image, a surface normal map, or edges. Current state-of-the-art deep generative models designed for such conditional image synthesis lack two important things: (1) they are unable to generate a large set of diverse outputs, due to the mode collapse problem. (2) they are not interpretable, making it difficult to control the synthesized output. We demonstrate that NN approaches potentially address such limitations, but suffer in accuracy on small datasets. We design a simple pipeline that combines the best of both worlds: the first stage uses a convolutional neural network (CNN) to maps the input to a (overly-smoothed) image, and the second stage uses a pixel-wise nearest neighbor method to map the smoothed output to multiple high-quality, high-frequency outputs in a controllable manner. We demonstrate our approach for various input modalities, and for various domains ranging from human faces to cats-and-dogs to shoes and handbags.

##### Abstract (translated by Google)
我们提出了一种简单的最近邻（NN）方法，它可以合成来自“不完整”信号（如低分辨率图像，表面法线贴图或边缘）的高频逼真图像。目前用于这种条件图像合成的最先进的深度生成模型缺乏两个重要的事情：（1）由于模式崩溃问题，它们不能产生大量不同的输出。 （2）它们不可解释，使得难以控制合成输出。我们证明神经网络方法可能解决这些限制，但在小数据集的准确性受到影响。我们设计了一个结合了两全其美的简单流水线：第一阶段使用卷积神经网络（CNN）将输入映射到（过平滑的）图像，第二阶段使用像素最近邻的方法来将平滑的输出以可控的方式映射到多个高质量的高频输出。我们展示了我们的各种输入模式的方法，以及各种领域，从人脸到猫，狗到鞋子和手袋。

##### URL
[https://arxiv.org/abs/1708.05349](https://arxiv.org/abs/1708.05349)

##### PDF
[https://arxiv.org/pdf/1708.05349](https://arxiv.org/pdf/1708.05349)

