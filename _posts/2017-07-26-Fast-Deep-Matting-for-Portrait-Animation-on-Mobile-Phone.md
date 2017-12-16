---
layout: post
title: "Fast Deep Matting for Portrait Animation on Mobile Phone"
date: 2017-07-26 05:05:48
categories: arXiv_CV
tags: arXiv_CV CNN
author: Bingke Zhu, Yingying Chen, Jinqiao Wang, Si Liu, Bo Zhang, Ming Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Image matting plays an important role in image and video editing. However, the formulation of image matting is inherently ill-posed. Traditional methods usually employ interaction to deal with the image matting problem with trimaps and strokes, and cannot run on the mobile phone in real-time. In this paper, we propose a real-time automatic deep matting approach for mobile devices. By leveraging the densely connected blocks and the dilated convolution, a light full convolutional network is designed to predict a coarse binary mask for portrait images. And a feathering block, which is edge-preserving and matting adaptive, is further developed to learn the guided filter and transform the binary mask into alpha matte. Finally, an automatic portrait animation system based on fast deep matting is built on mobile devices, which does not need any interaction and can realize real-time matting with 15 fps. The experiments show that the proposed approach achieves comparable results with the state-of-the-art matting solvers.

##### Abstract (translated by Google)
图像抠像在图像和视频编辑中起着重要的作用。然而，图像抠图的制定本质上是不适宜的。传统的方法通常采用交互方式来处理三维图形和笔画的图像拼接问题，而不能实时在手机上运行。在本文中，我们为移动设备提出了一种实时自动深度消除方法。通过利用密集连接的块和扩张卷积，设计了一个轻的全卷积网络来预测肖像图像的粗糙的二元掩模。并进一步开发了一种边缘保持和matting自适应的羽化块，以学习引导滤波器，并将二进制蒙板转换为alpha遮罩。最后，在移动设备上构建了基于快速深度消隐的自动人像动画系统，不需要任何交互，可实现15 fps的实时消光。实验表明，所提出的方法与最先进的消光解算器达到可比较的结果。

##### URL
[https://arxiv.org/abs/1707.08289](https://arxiv.org/abs/1707.08289)

##### PDF
[https://arxiv.org/pdf/1707.08289](https://arxiv.org/pdf/1707.08289)

