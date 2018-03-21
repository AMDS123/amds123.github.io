---
layout: post
title: "Convolutional Point-set Representation: A Convolutional Bridge Between a Densely Annotated Image and 3D Face Alignment"
date: 2018-03-17 17:20:25
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Yuhang Wu, Le Anh Vu Ha, Xiang Xu, Ioannis A. Kakadiaris
mathjax: true
---

* content
{:toc}

##### Abstract
We present a robust method for estimating the facial pose and shape information from a densely annotated facial image. The method relies on Convolutional Point-set Representation (CPR), a carefully designed matrix representation to summarize different layers of information encoded in the set of detected points in the annotated image. The CPR disentangles the dependencies of shape and different pose parameters and enables updating different parameters in a sequential manner via convolutional neural networks and recurrent layers. When updating the pose parameters, we sample reprojection errors along with a predicted direction and update the parameters based on the pattern of reprojection errors. This technique boosts the model's capability in searching a local minimum under challenging scenarios. We also demonstrate that annotation from different sources can be merged under the framework of CPR and contributes to outperforming the current state-of-the-art solutions for 3D face alignment. Experiments indicate the proposed CPRFA (CPR-based Face Alignment) significantly improves 3D alignment accuracy when the densely annotated image contains noise and missing values, which is common under "in-the-wild" acquisition scenarios.

##### Abstract (translated by Google)
我们提出了一个可靠的方法，用于从密集注释的面部图像中估计面部姿态和形状信息。该方法依赖于卷积点集表示（CPR），这是一种精心设计的矩阵表示法，用于汇总在注释图像中检测点集合中编码的不同信息层。 CPR解开形状和不同姿态参数的依赖关系，并且能够通过卷积神经网络和递归层以顺序方式更新不同的参数。在更新姿态参数时，我们对再投影误差和预测方向进行采样，并根据再投影误差的模式更新参数。这种技术提高了模型在挑战性场景下搜索局部最小值的能力。我们还证明，来自不同来源的注释可以在CPR框架下合并，并有助于超越当前最先进的3D人脸对齐解决方案。实验表明，当稠密注释的图像包含噪声和缺失值时，所提出的CPRFA（基于CPR的面对准）显着提高了3D对准精度，这在“野外”采集场景下很常见。

##### URL
[https://arxiv.org/abs/1803.06542](https://arxiv.org/abs/1803.06542)

##### PDF
[https://arxiv.org/pdf/1803.06542](https://arxiv.org/pdf/1803.06542)

