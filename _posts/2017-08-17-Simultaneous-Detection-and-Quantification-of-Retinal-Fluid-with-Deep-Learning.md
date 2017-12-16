---
layout: post
title: "Simultaneous Detection and Quantification of Retinal Fluid with Deep Learning"
date: 2017-08-17 23:31:05
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Deep_Learning Detection
author: Dustin Morley, Hassan Foroosh, Saad Shaikh, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new deep learning approach for automatic detection and segmentation of fluid within retinal OCT images. The proposed framework utilizes both ResNet and Encoder-Decoder neural network architectures. When training the network, we apply a novel data augmentation method called myopic warping together with standard rotation-based augmentation to increase the training set size to 45 times the original amount. Finally, the network output is post-processed with an energy minimization algorithm (graph cut) along with a few other knowledge guided morphological operations to finalize the segmentation process. Based on OCT imaging data and its ground truth from the RETOUCH challenge, the proposed system achieves dice indices of 0.522, 0.682, and 0.612, and average absolute volume differences of 0.285, 0.115, and 0.156 mm$^3$ for intaretinal fluid, subretinal fluid, and pigment epithelial detachment respectively.

##### Abstract (translated by Google)
我们提出了一种新的深层学习方法，用于自动检测和分割视网膜OCT图像中的液体。所提出的框架使用ResNet和编码器 - 解码器神经网络架构。当训练网络时，我们应用一种称为近视扭曲的新型数据增强方法和标准的基于旋转的增强，将训练集大小增加到原始数量的45倍。最后，将网络输出与能量最小化算法（图形切割）一起进行后处理以及一些其他知识指导的形态学操作以完成分割过程。基于来自RETOUCH挑战的OCT成像数据及其基础事实，所提出的系统达到0.522,0.682和0.612的骰子指数，并且视网膜下灌注液的平均绝对体积差为0.285,0.115和0.156mm 3 ^液体和色素上皮脱离。

##### URL
[https://arxiv.org/abs/1708.05464](https://arxiv.org/abs/1708.05464)

##### PDF
[https://arxiv.org/pdf/1708.05464](https://arxiv.org/pdf/1708.05464)

