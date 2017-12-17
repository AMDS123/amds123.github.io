---
layout: post
title: "Learning Steerable Filters for Rotation Equivariant CNNs"
date: 2017-11-21 22:59:29
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Maurice Weiler, Fred A. Hamprecht, Martin Storath
mathjax: true
---

* content
{:toc}

##### Abstract
In many machine learning tasks it is desirable that a model's prediction transforms in an equivariant way under transformations of its input. Convolutional neural networks (CNNs) implement translational equivariance by construction; for other transformations, however, they are compelled to learn the proper mapping. In this work, we develop Steerable Filter CNNs (SFCNNs) which achieve joint equivariance under translations and rotations by design. The proposed architecture employs steerable filters to efficiently compute orientation dependent responses for many orientations without suffering interpolation artifacts from filter rotation. We utilize group convolutions which guarantee an equivariant mapping. In addition, we generalize He's weight initialization scheme to filters which are defined as a linear combination of a system of atomic filters. Numerical experiments show a substantial enhancement of the sample complexity with a growing number of sampled filter orientations and confirm that the network generalizes learned patterns over orientations. The proposed approach achieves state-of-the-art on the rotated MNIST benchmark and on the ISBI 2012 2D EM segmentation challenge.

##### Abstract (translated by Google)
在许多机器学习任务中，希望模型的预测在其输入的变换下以同样的方式变换。卷积神经网络（CNN）通过施工实现平移等变性;但是，对于其他转换，他们不得不学习正确的映射。在这项工作中，我们开发了可转换滤波器CNNs（SFCNNs），在设计的翻译和旋转下实现联合等变性。所提出的架构使用可操纵滤波器来高效地计算针对多个方向的取向依赖响应，而不会遭受滤波器旋转的内插伪影。我们利用确保等变映射的群卷积。另外，我们将He的权重初始化方案推广到被定义为原子过滤器系统的线性组合的过滤器。数值实验显示，随着采样滤波器取向数量的增加，样本复杂度显着提高，并确认网络在方向上概括了学习模式。所提出的方法在旋转的MNIST基准和ISBI 2012 2D EM分割挑战中实现了最新的技术。

##### URL
[https://arxiv.org/abs/1711.07289](https://arxiv.org/abs/1711.07289)

##### PDF
[https://arxiv.org/pdf/1711.07289](https://arxiv.org/pdf/1711.07289)

