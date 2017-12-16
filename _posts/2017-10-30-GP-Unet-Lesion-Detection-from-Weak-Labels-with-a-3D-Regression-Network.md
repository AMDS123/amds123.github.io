---
layout: post
title: "GP-Unet: Lesion Detection from Weak Labels with a 3D Regression Network"
date: 2017-10-30 09:46:11
categories: arXiv_CV
tags: arXiv_CV Salient GAN CNN Detection
author: Florian Dubost, Gerda Bortsova, Hieab Adams, Arfan Ikram, Wiro Niessen, Meike Vernooij, Marleen De Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel convolutional neural network for lesion detection from weak labels. Only a single, global label per image - the lesion count - is needed for training. We train a regression network with a fully convolutional architecture combined with a global pooling layer to aggregate the 3D output into a scalar indicating the lesion count. When testing on unseen images, we first run the network to estimate the number of lesions. Then we remove the global pooling layer to compute localization maps of the size of the input image. We evaluate the proposed network on the detection of enlarged perivascular spaces in the basal ganglia in MRI. Our method achieves a sensitivity of 62% with on average 1.5 false positives per image. Compared with four other approaches based on intensity thresholding, saliency and class maps, our method has a 20% higher sensitivity.

##### Abstract (translated by Google)
我们提出了一个新的卷积神经网络从弱标签的病变检测。培训需要每个图像只有一个单一的全球标签 - 病灶数量。我们训练了一个完全卷积体系结构与全局共享层结合的回归网络，将3D输出聚合成一个表示损伤计数的标量。当对未见的图像进行测试时，我们首先运行网络来估计病变的数量。然后，我们删除全局池图层来计算输入图像大小的本地化图。我们评估提出的网络在MRI检查基底节放大的血管周围间隙。我们的方法达到了62％的灵敏度，平均每个图像有1.5个误报。与其他四种基于强度阈值，显着性和类别图的方法相比，我们的方法具有高出20％的灵敏度。

##### URL
[https://arxiv.org/abs/1705.07999](https://arxiv.org/abs/1705.07999)

##### PDF
[https://arxiv.org/pdf/1705.07999](https://arxiv.org/pdf/1705.07999)

