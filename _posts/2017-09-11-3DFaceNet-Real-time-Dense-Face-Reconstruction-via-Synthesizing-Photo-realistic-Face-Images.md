---
layout: post
title: "3DFaceNet: Real-time Dense Face Reconstruction via Synthesizing Photo-realistic Face Images"
date: 2017-09-11 11:32:01
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Yudong Guo, Juyong Zhang, Jianfei Cai, Boyi Jiang, Jianmin Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
With the powerfulness of convolution neural networks (CNN), CNN based face reconstruction has recently shown promising performance in reconstructing detailed face shape from 2D face images. The success of CNN-based methods relies on a large number of labeled data. The state-of-the-art synthesizes such data using a coarse morphable face model, which however has difficulty to generate detailed photo-realistic images of faces (with wrinkles). This paper presents a novel face data generation method. Specifically, we render a large number of photo-realistic face images with different attributes based on inverse rendering. Furthermore, we construct a fine-detailed face image dataset by transferring different scales of details from one image to another. We also construct a large number of video-type adjacent frame pairs by simulating the distribution of real video data. With these nicely constructed datasets, we propose a coarse-to-fine learning framework consisting of three convolutional networks. The networks are trained for real-time detailed 3D face reconstruction from monocular video as well as from a single image. Extensive experimental results demonstrate that our framework can produce high-quality reconstruction but with much less computation time compared to the state-of-the-art. Moreover, our method is robust to pose, expression and lighting due to the diversity of data.

##### Abstract (translated by Google)
随着卷积神经网络（CNN）的强大性，基于CNN的人脸重构最近在二维人脸图像重建人脸的细节方面表现出前景。基于CNN的方法的成功依赖于大量的标记数据。最先进的技术使用粗糙的形变人脸模型来合成这样的数据，但是难以生成详细的照片般逼真的人脸图像（具有皱纹）。本文提出了一种新的人脸数据生成方法。具体来说，我们渲染大量的具有不同属性的照片般逼真的人脸图像。此外，我们通过将不同比例的细节从一个图像转移到另一个图像来构建精细的人脸图像数据集。我们还通过模拟实际视频数据的分布来构建大量视频类型的相邻帧对。有了这些精心构建的数据集，我们提出了一个由三个卷积网络组成的从粗到精的学习框架。网络训练用于从单眼视频以及从单个图像实时详细的3D面部重建。广泛的实验结果表明，我们的框架可以产生高质量的重建，但与现有技术相比，计算时间更少。而且，由于数据的多样性，我们的方法对于姿态，表情和照明具有很强的鲁棒性。

##### URL
[https://arxiv.org/abs/1708.00980](https://arxiv.org/abs/1708.00980)

##### PDF
[https://arxiv.org/pdf/1708.00980](https://arxiv.org/pdf/1708.00980)

