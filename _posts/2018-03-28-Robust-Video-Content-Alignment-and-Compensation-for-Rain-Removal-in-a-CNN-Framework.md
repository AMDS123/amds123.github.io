---
layout: post
title: "Robust Video Content Alignment and Compensation for Rain Removal in a CNN Framework"
date: 2018-03-28 07:22:10
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Jie Chen, Cheen-Hau Tan, Junhui Hou, Lap-Pui Chau, He Li
mathjax: true
---

* content
{:toc}

##### Abstract
Rain removal is important for improving the robustness of outdoor vision based systems. Current rain removal methods show limitations either for complex dynamic scenes shot from fast moving cameras, or under torrential rain fall with opaque occlusions. We propose a novel derain algorithm, which applies superpixel (SP) segmentation to decompose the scene into depth consistent units. Alignment of scene contents are done at the SP level, which proves to be robust towards rain occlusion and fast camera motion. Two alignment output tensors, i.e., optimal temporal match tensor and sorted spatial-temporal match tensor, provide informative clues for rain streak location and occluded background contents to generate an intermediate derain output. These tensors will be subsequently prepared as input features for a convolutional neural network to restore high frequency details to the intermediate output for compensation of mis-alignment blur. Extensive evaluations show that up to 5 dB reconstruction PSNR advantage is achieved over state-of-the-art methods. Visual inspection shows that much cleaner rain removal is achieved especially for highly dynamic scenes with heavy and opaque rainfall from a fast moving camera.

##### Abstract (translated by Google)
除雨对于提高基于户外视觉的系统的鲁棒性非常重要。目前的降雨方法对于快速移动摄像机拍摄的复杂动态场景或暴露在不透明遮挡下的暴雨下降显示出局限性。我们提出了一种新颖的derain算法，它应用超像素（SP）分割将场景分解成深度一致的单元。在SP级完成场景内容的对齐，这对于雨遮挡和快速摄像机运动是有力的。两个对准输出张量，即最佳时间匹配张量和排序的空间 - 时间匹配张量，为雨条位置和遮挡的背景内容提供信息线索以生成中间的输出。随后将这些张量准备为卷积神经网络的输入特征，以将高频细节恢复到中间输出以补偿失准模糊。广泛的评估表明，与最先进的方法相比，可实现高达5 dB的重建PSNR优势。目视检查表明，除了快速移动的相机带来的沉重而不透明的高度动态场景外，还可以实现更清洁的雨水清除。

##### URL
[https://arxiv.org/abs/1803.10433](https://arxiv.org/abs/1803.10433)

##### PDF
[https://arxiv.org/pdf/1803.10433](https://arxiv.org/pdf/1803.10433)

