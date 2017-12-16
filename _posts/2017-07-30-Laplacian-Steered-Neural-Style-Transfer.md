---
layout: post
title: "Laplacian-Steered Neural Style Transfer"
date: 2017-07-30 15:46:17
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN Optimization
author: Shaohua Li, Xinxing Xu, Liqiang Nie, Tat-Seng Chua
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Style Transfer based on Convolutional Neural Networks (CNN) aims to synthesize a new image that retains the high-level structure of a content image, rendered in the low-level texture of a style image. This is achieved by constraining the new image to have high-level CNN features similar to the content image, and lower-level CNN features similar to the style image. However in the traditional optimization objective, low-level features of the content image are absent, and the low-level features of the style image dominate the low-level detail structures of the new image. Hence in the synthesized image, many details of the content image are lost, and a lot of inconsistent and unpleasing artifacts appear. As a remedy, we propose to steer image synthesis with a novel loss function: the Laplacian loss. The Laplacian matrix ("Laplacian" in short), produced by a Laplacian operator, is widely used in computer vision to detect edges and contours. The Laplacian loss measures the difference of the Laplacians, and correspondingly the difference of the detail structures, between the content image and a new image. It is flexible and compatible with the traditional style transfer constraints. By incorporating the Laplacian loss, we obtain a new optimization objective for neural style transfer named Lapstyle. Minimizing this objective will produce a stylized image that better preserves the detail structures of the content image and eliminates the artifacts. Experiments show that Lapstyle produces more appealing stylized images with less artifacts, without compromising their "stylishness".

##### Abstract (translated by Google)
基于卷积神经网络（Neural Style Transfer，CNN）的神经风格转换旨在合成一个新的图像，保留一个内容图像的高层次结构，呈现在一个风格图像的低层纹理中。这是通过限制新图像具有类似于内容图像的高级CNN特征和与类型图像相似的低级CNN特征来实现的。然而，在传统的优化目标中，内容图像的低级特征缺失，而风格图像的低级特征主导着新图像的低级细节结构。因此，在合成图像中，内容图像的许多细节丢失，并且出现许多不一致和不愉快的伪像。作为一种补救措施，我们提出用一种新的损失函数来控制图像合成：拉普拉斯损失。由拉普拉斯算子生成的拉普拉斯矩阵（Laplacian matrix）（简称拉普拉斯算子）被广泛用于计算机视觉检测边缘和轮廓。拉普拉斯损失度量了拉普拉斯算子的差异，并相应地考察了内容图像与新图像之间的细节结构差异。它灵活且兼容传统的风格转移限制。通过结合拉普拉斯损失，我们获得了一个名为Lapstyle的神经风格转移的新优化目标。最小化这个目标将产生一个风格化的图像，更好地保留了内容图像的细节结构，并消除了文物。实验表明，Lapstyle产生更具吸引力的程式化的图像与较少的文物，不妥协的“时尚性”。

##### URL
[https://arxiv.org/abs/1707.01253](https://arxiv.org/abs/1707.01253)

##### PDF
[https://arxiv.org/pdf/1707.01253](https://arxiv.org/pdf/1707.01253)

