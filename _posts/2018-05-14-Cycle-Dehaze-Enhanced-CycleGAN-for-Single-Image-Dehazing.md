---
layout: post
title: "Cycle-Dehaze: Enhanced CycleGAN for Single Image Dehazing"
date: 2018-05-14 17:34:21
categories: arXiv_CV
tags: arXiv_CV GAN Deep_Learning Quantitative
author: Deniz Engin, Anıl Genç, Hazım Kemal Ekenel
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an end-to-end network, called Cycle-Dehaze, for single image dehazing problem, which does not require pairs of hazy and corresponding ground truth images for training. That is, we train the network by feeding clean and hazy images in an unpaired manner. Moreover, the proposed approach does not rely on estimation of the atmospheric scattering model parameters. Our method enhances CycleGAN formulation by combining cycle-consistency and perceptual losses in order to improve the quality of textural information recovery and generate visually better haze-free images. Typically, deep learning models for dehazing take low resolution images as input and produce low resolution outputs. However, in the NTIRE 2018 challenge on single image dehazing, high resolution images were provided. Therefore, we apply bicubic downscaling. After obtaining low-resolution outputs from the network, we utilize the Laplacian pyramid to upscale the output images to the original resolution. We conduct experiments on NYU-Depth, I-HAZE, and O-HAZE datasets. Extensive experiments demonstrate that the proposed approach improves CycleGAN method both quantitatively and qualitatively.

##### Abstract (translated by Google)
在本文中，我们提出了一种称为Cycle-Dehaze的端到端网络，用于单个图像去雾问题，它不需要用于训练的朦胧和相应的地面真实图像对。也就是说，我们通过以不成对的方式提供干净和模糊的图像来训练网络。此外，所提出的方法不依赖于大气散射模型参数的估计。我们的方法通过结合循环一致性和感知损失来增强CycleGAN公式，以提高纹理信息恢复的质量并生成视觉上更好的无雾图像。通常，用于去雾的深度学习模型将低分辨率图像作为输入并产生低分辨率输出。但是，在NTIRE 2018对单幅图像除雾的挑战中，提供了高分辨率图像。因此，我们应用双三次降尺度。在从网络获得低分辨率输出后，我们利用拉普拉斯金字塔将输出图像放大至原始分辨率。我们在NYU-Depth，I-HAZE和O-HAZE数据集上进行实验。大量的实验表明，所提出的方法在数量上和质量上改进了CycleGAN方法。

##### URL
[https://arxiv.org/abs/1805.05308](https://arxiv.org/abs/1805.05308)

##### PDF
[https://arxiv.org/pdf/1805.05308](https://arxiv.org/pdf/1805.05308)

