---
layout: post
title: "PointFlowNet: Learning Representations for 3D Scene Flow Estimation from Point Clouds"
date: 2018-06-06 13:24:30
categories: arXiv_CV
tags: arXiv_CV Inference
author: Aseem Behl, Despoina Paschalidou, Simon Donn&#xe9;, Andreas Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
Despite significant progress in image-based 3D scene flow estimation, the performance of such approaches has not yet reached the fidelity required by many applications. Simultaneously, these applications are often not restricted to image-based estimation: laser scanners provide a popular alternative to traditional cameras, for example in the context of self-driving cars, as they directly yield a 3D point cloud. In this paper, we propose to estimate 3D scene flow from such unstructured point clouds using a deep neural network. In a single forward pass, our model jointly predicts 3D scene flow as well as the 3D bounding box and rigid body motion of objects in the scene. While the prospect of estimating 3D scene flow from unstructured point clouds is promising, it is also a challenging task. We show that the traditional global representation of rigid body motion prohibits inference by CNNs, and propose a translation equivariant representation to circumvent this problem. For training our deep network, a large dataset is required. Because of this, we augment real scans from KITTI with virtual objects, realistically modeling occlusions and simulating sensor noise. A thorough comparison with classic and learning-based techniques highlights the robustness of the proposed approach.

##### Abstract (translated by Google)
尽管基于图像的3D场景流量估计取得了重大进展，但这些方法的性能尚未达到许多应用程序所要求的保真度。同时，这些应用通常不限于基于图像的估计：激光扫描仪提供了一种传统相机的流行替代方案，例如在自动驾驶汽车的情况下，因为它们直接产生3D点云。在本文中，我们提出使用深度神经网络从这种非结构化点云中估计三维场景流。在单次正向通道中，我们的模型共同预测场景中的三维场景流以及物体的三维边界框和刚体运动。尽管从非结构化点云估计3D场景流的前景看好，但这也是一项具有挑战性的任务。我们表明，刚体运动的传统全局表示禁止CNN推理，并提出一个翻译等变表示法来规避这个问题。为了训练我们的深层网络，需要大型数据集。正因为如此，我们用虚拟物体增强KITTI的实际扫描，真实地模拟遮挡和模拟传感器噪声。与传统和基于学习的技术进行彻底比较，凸显了该方法的稳健性。

##### URL
[http://arxiv.org/abs/1806.02170](http://arxiv.org/abs/1806.02170)

##### PDF
[http://arxiv.org/pdf/1806.02170](http://arxiv.org/pdf/1806.02170)

