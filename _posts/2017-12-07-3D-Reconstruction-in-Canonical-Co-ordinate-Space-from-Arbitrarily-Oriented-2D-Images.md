---
layout: post
title: "3D Reconstruction in Canonical Co-ordinate Space from Arbitrarily Oriented 2D Images"
date: 2017-12-07 18:55:18
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Quantitative
author: Benjamin Hou, Bishesh Khanal, Amir Alansary, Steven McDonagh, Alice Davidson, Mary Rutherford, Jo V. Hajnal, Daniel Rueckert, Ben Glocker, Bernhard Kainz
mathjax: true
---

* content
{:toc}

##### Abstract
Limited capture range and the requirement to provide high quality initialisation for optimisation-based 2D/3D image registration methods can significantly degrade the performance of 3D image reconstruction and motion compensation pipelines. Challenging clinical imaging scenarios, which contain significant subject motion such as fetal in-utero imaging, complicate the 3D image and volume reconstruction process. In this paper we present a learning based image registration method capable of predicting 3D rigid transformations of arbitrarily oriented 2D image slices, with respect to a learned canonical atlas co-ordinate system. Only image slice intensity information is used to perform registration and canonical alignment, no spatial transform initialisation is required. To find image transformations we utilise a Convolutional Neural Network (CNN) architecture to learn the regression function capable of mapping 2D image slices to a 3D canonical atlas space. We extensively evaluate the effectiveness of our approach quantitatively on simulated Magnetic Resonance Imaging (MRI), fetal brain imagery with synthetic motion and further demonstrate qualitative results on real fetal MRI data where our method is integrated into a full reconstruction and motion compensation pipeline. Our learning based registration achieves an average spatial prediction error of 7 mm on simulated data and produces qualitatively improved reconstructions for heavily moving fetuses with gestational ages of approximately 20 weeks. Our model provides a general and computationally efficient solution to the 2D/3D registration initialisation problem and is suitable for real-time scenarios.

##### Abstract (translated by Google)
有限的捕获范围和为基于优化的2D / 3D图像配准方法提供高质量初始化的要求可能显着降低3D图像重构和运动补偿管线的性能。具有挑战性的临床成像方案，包含显着的对象运动，如胎儿宫内成像，使三维图像和体积重建过程变得复杂。在本文中，我们提出了一种基于学习的图像配准方法，能够预测任意取向的二维图像切片的三维刚性变换，关于学习的典型图谱坐标系统。仅使用图像切片强度信息来执行配准和规范对齐，不需要空间变换初始化。为了找到图像变换，我们利用卷积神经网络（CNN）体系结构来学习能够将2D图像切片映射到3D典型图谱空间的回归函数。我们广泛地评估了我们的方法在模拟的磁共振成像（MRI），合成运动胎儿大脑图像定量的有效性，并进一步展示了真正的胎儿MRI数据的定性结果，我们的方法被集成到一个完整的重建和运动补偿管道。我们的基于学习的注册在模拟数据上实现了7毫米的平均空间预测误差，并对胎龄为大约20周的重度移动胎儿进行定性改进的重建。我们的模型为2D / 3D注册初始化问题提供了一个通用且计算效率高的解决方案，适用于实时场景。

##### URL
[http://arxiv.org/abs/1709.06341](http://arxiv.org/abs/1709.06341)

##### PDF
[http://arxiv.org/pdf/1709.06341](http://arxiv.org/pdf/1709.06341)

