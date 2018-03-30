---
layout: post
title: "HDM-Net: Monocular Non-Rigid 3D Reconstruction with Learned Deformation Model"
date: 2018-03-27 17:31:47
categories: arXiv_CV
tags: arXiv_CV Face Tracking
author: Vladislav Golyanik, Soshi Shimada, Kiran Varanasi, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
Monocular dense 3D reconstruction of deformable objects is a hard ill-posed problem in computer vision. Current techniques either require dense correspondences and rely on motion and deformation cues, or assume a highly accurate reconstruction (referred to as a template) of at least a single frame given in advance and operate in the manner of non-rigid tracking. Accurate computation of dense point tracks often requires multiple frames and might be computationally expensive. Availability of a template is a very strong prior which restricts system operation to a pre-defined environment and scenarios. In this work, we propose a new hybrid approach for monocular non-rigid reconstruction which we call Hybrid Deformation Model Network (HDM-Net). In our approach, deformation model is learned by a deep neural network, with a combination of domain-specific loss functions. We train the network with multiple states of a non-rigidly deforming structure with a known shape at rest. HDM-Net learns different reconstruction cues including texture-dependent surface deformations, shading and contours. We show generalisability of HDM-Net to states not presented in the training dataset, with unseen textures and under new illumination conditions. Experiments with noisy data and a comparison with other methods demonstrate robustness and accuracy of the proposed approach and suggest possible application scenarios of the new technique in interventional diagnostics and augmented reality.

##### Abstract (translated by Google)
可变形物体的单目密集三维重建是计算机视觉中的一个难以解决的问题。目前的技术要么需要密集的对应关系，要依赖于运动和变形线索，或者假设预先给出的至少一个单帧的高度准确的重建（称为模板），并以非刚性跟踪的方式进行操作。准确计算密集点轨迹通常需要多个帧，并且可能在计算上是昂贵的。模板的可用性是一个非常强大的优先事项，它将系统操作限制在预定义的环境和场景中。在这项工作中，我们提出了一种新的单目非刚性重建混合方法，我们称之为混合变形模型网络（HDM-Net）。在我们的方法中，变形模型是通过深度神经网络学习的，结合了特定领域的损失函数。我们训练网络具有已知形状的非刚性变形结构的多个状态。 HDM-Net学习不同的重建线索，包括纹理相关的表面变形，阴影和轮廓。我们展示了HDM-Net的一般性，即在训练数据集中没有呈现的状态，具有看不见的纹理以及在新的照明条件下。噪声数据的实验以及与其他方法的比较证明了所提出方法的稳健性和准确性，并提出了介入诊断和增强现实中新技术的可能应用场景。

##### URL
[https://arxiv.org/abs/1803.10193](https://arxiv.org/abs/1803.10193)

##### PDF
[https://arxiv.org/pdf/1803.10193](https://arxiv.org/pdf/1803.10193)

