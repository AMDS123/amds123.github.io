---
layout: post
title: "CocoNet: A deep neural network for mapping pixel coordinates to color values"
date: 2018-08-31 13:08:28
categories: arXiv_CV
tags: arXiv_CV Knowledge Quantitative
author: Paul Andrei Bricman, Radu Tudor Ionescu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a deep neural network approach for mapping the 2D pixel coordinates in an image to the corresponding Red-Green-Blue (RGB) color values. The neural network is termed CocoNet, i.e. coordinates-to-color network. During the training process, the neural network learns to encode the input image within its layers. More specifically, the network learns a continuous function that approximates the discrete RGB values sampled over the discrete 2D pixel locations. At test time, given a 2D pixel coordinate, the neural network will output the approximate RGB values of the corresponding pixel. By considering every 2D pixel location, the network can actually reconstruct the entire learned image. It is important to note that we have to train an individual neural network for each input image, i.e. one network encodes a single image only. To the best of our knowledge, we are the first to propose a neural approach for encoding images individually, by learning a mapping from the 2D pixel coordinate space to the RGB color space. Our neural image encoding approach has various low-level image processing applications ranging from image encoding, image compression and image denoising to image resampling and image completion. We conduct experiments that include both quantitative and qualitative results, demonstrating the utility of our approach and its superiority over standard baselines, e.g. bilateral filtering or bicubic interpolation. Our code is available at https://github.com/paubric/python-fuse-coconet.

##### Abstract (translated by Google)
在本文中，我们提出了一种深度神经网络方法，用于将图像中的2D像素坐标映射到相应的红 - 绿 - 蓝（RGB）颜色值。神经网络被称为CocoNet，即坐标到彩色网络。在训练过程中，神经网络学习在其层内编码输入图像。更具体地，网络学习连续函数，该函数近似在离散2D像素位置上采样的离散RGB值。在测试时，给定2D像素坐标，神经网络将输出相应像素的近似RGB值。通过考虑每个2D像素位置，网络实际上可以重建整个学习图像。重要的是要注意，我们必须为每个输入图像训练单独的神经网络，即一个网络仅编码单个图像。据我们所知，我们是第一个通过学习从2D像素坐标空间到RGB颜色空间的映射来提出单独编码图像的神经方法。我们的神经图像编码方法具有各种低级图像处理应用，从图像编码，图像压缩和图像去噪到图像重采样和图像完成。我们进行的实验包括定量和定性结果，证明了我们的方法的实用性及其优于标准基线的优势，例如：双边滤波或双三次插值。我们的代码可在https://github.com/paubric/python-fuse-coconet上找到。

##### URL
[http://arxiv.org/abs/1805.11357](http://arxiv.org/abs/1805.11357)

##### PDF
[http://arxiv.org/pdf/1805.11357](http://arxiv.org/pdf/1805.11357)

