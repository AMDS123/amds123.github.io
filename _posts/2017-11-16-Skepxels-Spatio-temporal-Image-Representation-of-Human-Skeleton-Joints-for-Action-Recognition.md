---
layout: post
title: "Skepxels: Spatio-temporal Image Representation of Human Skeleton Joints for Action Recognition"
date: 2017-11-16 06:03:52
categories: arXiv_CV
tags: arXiv_CV Image_Caption Action_Recognition Relation Recognition
author: Jian Liu, Naveed Akhtar, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
Human skeleton joints are popular for action analysis since they can be easily extracted from videos to discard background noises. However, current skeleton representations do not fully benefit from machine learning with CNNs. We propose "Skepxels" a spatio-temporal representation for skeleton sequences to fully exploit the "local" correlations between joints using the 2D convolution kernels of CNN. We transform skeleton videos into images of flexible dimensions using Skepxels and develop a CNN-based framework for effective human action recognition using the resulting images. Skepxels encode rich spatio-temporal information about the skeleton joints in the frames by maximizing a unique distance metric, defined collaboratively over the distinct joint arrangements used in the skeletal image. Moreover, they are flexible in encoding compound semantic notions such as location and speed of the joints. The proposed action recognition exploits the representation in a hierarchical manner by first capturing the micro-temporal relations between the skeleton joints with the Skepxels and then exploiting their macro-temporal relations by computing the Fourier Temporal Pyramids over the CNN features of the skeletal images. We extend the Inception-ResNet CNN architecture with the proposed method and improve the state-of-the-art accuracy by 4.4% on the large scale NTU human activity dataset. On the medium-sized N-UCLA and UTH-MHAD datasets, our method outperforms the existing results by 5.7% and 9.3% respectively.

##### Abstract (translated by Google)
人的骨骼关节是流行的行动分析，因为他们可以很容易地从视频中提取丢弃背景噪音。但是，目前的骨架表示并没有完全从CNN的机器学习中受益。我们提出“Skepxels”骨架序列的时空表示，充分利用CNN二维卷积核的关节之间的“局部”相关性。我们使用Skepxels将骨架视频转换为灵活尺寸的图像，并使用所得图像开发基于CNN的有效人体动作识别框架。 SkePPel通过最大化独特的距离度量来编码关于帧中的骨架关节的丰富的时空信息，所述距离度量在骨骼图像中使用的不同的联合布置上协作地定义。此外，它们在编码复合语义概念（如关节的位置和速度）方面灵活。所提出的动作识别通过首先捕捉骨骼关节与SkePel之间的微时间关系，然后利用其宏观 - 时间关系，通过计算骨骼图像的CNN特征上的傅里叶时间金字塔来利用该表示。我们使用所提出的方法扩展了Inception-ResNet CNN架构，并在大规模的NTU人类活动数据集上提高了4.4％的最新准确度。在中等大小的N-UCLA和UTH-MHAD数据集上，我们的方法分别比现有的结果高出5.7％和9.3％。

##### URL
[https://arxiv.org/abs/1711.05941](https://arxiv.org/abs/1711.05941)

##### PDF
[https://arxiv.org/pdf/1711.05941](https://arxiv.org/pdf/1711.05941)

