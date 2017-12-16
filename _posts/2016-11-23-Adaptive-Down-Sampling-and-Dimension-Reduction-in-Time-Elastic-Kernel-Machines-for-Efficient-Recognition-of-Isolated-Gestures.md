---
layout: post
title: "Adaptive Down-Sampling and Dimension Reduction in Time Elastic Kernel Machines for Efficient Recognition of Isolated Gestures"
date: 2016-11-23 13:18:17
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Pierre-François Marteau (EXPRESSION), Sylvie Gibet (EXPRESSION), Clément Reverdy (EXPRESSION)
mathjax: true
---

* content
{:toc}

##### Abstract
In the scope of gestural action recognition, the size of the feature vector representing movements is in general quite large especially when full body movements are considered. Furthermore, this feature vector evolves during the movement performance so that a complete movement is fully represented by a matrix M of size DxT , whose element M i, j represents the value of feature i at timestamps j. Many studies have addressed dimensionality reduction considering only the size of the feature vector lying in R D to reduce both the variability of gestural sequences expressed in the reduced space, and the computational complexity of their processing. In return, very few of these methods have explicitly addressed the dimensionality reduction along the time axis. Yet this is a major issue when considering the use of elastic distances which are characterized by a quadratic complexity along the time axis. We present in this paper an evaluation of straightforward approaches aiming at reducing the dimensionality of the matrix M for each movement, leading to consider both the dimensionality reduction of the feature vector as well as its reduction along the time axis. The dimensionality reduction of the feature vector is achieved by selecting remarkable joints in the skeleton performing the movement, basically the extremities of the articulatory chains composing the skeleton. The temporal dimen-sionality reduction is achieved using either a regular or adaptive down-sampling that seeks to minimize the reconstruction error of the movements. Elastic and Euclidean kernels are then compared through support vector machine learning. Two data sets 1 that are widely referenced in the domain of human gesture recognition, and quite distinctive in terms of quality of motion capture, are used for the experimental assessment of the proposed approaches. On these data sets we experimentally show that it is feasible, and possibly desirable, to significantly reduce simultaneously the size of the feature vector and the number of skeleton frames to represent body movements while maintaining a very good recognition rate. The method proves to give satisfactory results at a level currently reached by state-of-the-art methods on these data sets. We experimentally show that the computational complexity reduction that is obtained makes this approach eligible for real-time applications.

##### Abstract (translated by Google)
在姿势动作识别的范围中，表示运动的特征矢量的大小通常相当大，特别是当考虑全身运动时。此外，该特征矢量在运动过程中演变，使得完整的运动完全由尺寸为D×T的矩阵M表示，其元素M i，j表示在时间戳j处的特征i的值。许多研究都只考虑位于R D中的特征向量的大小来降低降维以减少在减小的空间中表示的姿势序列的可变性以及其处理的计算复杂度。作为回报，这些方法中很少有明确提出沿时间轴的降维。然而当考虑使用沿时间轴具有二次复杂性特征的弹性距离时，这是一个主要问题。我们在本文中提出了一个简单的方法，旨在降低每个运动的矩阵M的维度的评估，导致既考虑特征向量的维数减少又考虑其沿时间轴的减少。特征向量的降维是通过在运动的骨架中选择显着的关节来实现的，基本上是组成骨架的关节链的末端。时间维数减少是通过使用正则或自适应下采样来实现的，该下采样旨在最小化运动的重构误差。然后通过支持向量机学习来比较弹性和欧几里德核。在人类手势识别领域被广泛引用的两个数据集1，并且在运动捕获质量方面非常独特，被用于所提出的方法的实验评估。在这些数据集上，我们通过实验证明，在保持非常好的识别率的同时，显着减少特征矢量的大小和表示身体运动的骨架帧的数量是可行的，并且可能是期望的。该方法证明在这些数据集上现有技术方法所达到的水平上给出了令人满意的结果。我们通过实验证明，获得的计算复杂度降低使得这种方法适用于实时应用程序。

##### URL
[https://arxiv.org/abs/1611.07781](https://arxiv.org/abs/1611.07781)

##### PDF
[https://arxiv.org/pdf/1611.07781](https://arxiv.org/pdf/1611.07781)

