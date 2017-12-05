---
layout: post
title:  'Spatial PixelCNN: Generating Images from Patches'
date:   2017-12-05 18:44:29
categories: CV
tags: CV
author: Nader Akoury, Anh Nguyen
---

* content
{:toc}

##### Abstract
In this paper we propose Spatial PixelCNN, a conditional autoregressive model that generates images from small patches. By conditioning on a grid of pixel coordinates and global features extracted from a Variational Autoencoder (VAE), we are able to train on patches of images, and reproduce the full-sized image. We show that it not only allows for generating high quality samples at the same resolution as the underlying dataset, but is also capable of upscaling images to arbitrary resolutions (tested at resolutions up to $50\times$) on the MNIST dataset. Compared to a PixelCNN++ baseline, Spatial PixelCNN quantitatively and qualitatively achieves similar performance on the MNIST dataset.

##### Abstract (translated by Google)
在本文中，我们提出空间PixelCNN，一个条件自回归模型，从小补丁生成图像。通过对从变分自动编码器（VAE）提取的像素坐标和全局特征网格进行调节，我们能够对图像块进行训练，并重现全尺寸图像。我们表明，它不仅可以生成与基础数据集相同分辨率的高质量样本，还​​可以在MNIST数据集上将图像放大到任意分辨率（在高达50美元的分辨率下进行测试）。与PixelCNN ++基线相比，Spatial PixelCNN在数量和质量上都能在MNIST数据集上实现类似的性能。

