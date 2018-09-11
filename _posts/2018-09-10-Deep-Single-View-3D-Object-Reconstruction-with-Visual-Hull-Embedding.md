---
layout: post
title: "Deep Single-View 3D Object Reconstruction with Visual Hull Embedding"
date: 2018-09-10 16:49:36
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Embedding CNN
author: Hanqing Wang, Jiaolong Yang, Wei Liang, Xin Tong
mathjax: true
---

* content
{:toc}

##### Abstract
3D object reconstruction is a fundamental task of many robotics and AI problems. With the aid of deep convolutional neural networks (CNNs), 3D object reconstruction has witnessed a significant progress in recent years. However, possibly due to the prohibitively high dimension of the 3D object space, the results from deep CNNs are often prone to missing some shape details. In this paper, we present an approach which aims to preserve more shape details and improve the reconstruction quality. The key idea of our method is to leverage object mask and pose estimation from CNNs to assist the 3D shape learning by constructing a probabilistic single-view visual hull inside of the network. Our method works by first predicting a coarse shape as well as the object pose and silhouette using CNNs, followed by a novel 3D refinement CNN which refines the coarse shapes using the constructed probabilistic visual hulls. Experiment on both synthetic data and real images show that embedding a single-view visual hull for shape refinement can significantly improve the reconstruction quality by recovering more shapes details and improving shape consistency with the input image.

##### Abstract (translated by Google)
3D对象重建是许多机器人和AI问题的基本任务。借助深度卷积神经网络（CNN），近年来三维物体重建取得了重大进展。然而，可能由于3D对象空间的高度过高，来自深CNN的结果通常易于丢失一些形状细节。在本文中，我们提出了一种旨在保留更多形状细节和提高重建质量的方法。我们的方法的关键思想是利用来自CNN的对象掩模和姿势估计来通过在网络内构建概率单视图视觉外壳来辅助3D形状学习。我们的方法首先使用CNN预测粗糙形状以及对象姿势和轮廓，然后使用新建的3D细化CNN，使用构造的概率视觉外壳细化粗糙形状。对合成数据和真实图像的实验表明，嵌入单视图视觉外壳进行形状细化可以通过恢复更多形状细节并改善输入图像的形状一致性来显着提高重建质量。

##### URL
[http://arxiv.org/abs/1809.03451](http://arxiv.org/abs/1809.03451)

##### PDF
[http://arxiv.org/pdf/1809.03451](http://arxiv.org/pdf/1809.03451)

