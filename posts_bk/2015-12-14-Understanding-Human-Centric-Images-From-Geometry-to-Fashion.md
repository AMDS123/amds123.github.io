---
layout: post
title: "Understanding Human-Centric Images: From Geometry to Fashion"
date: 2015-12-14 03:15:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation CNN Semantic_Segmentation
author: Edgar Simo-Serra
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding humans from photographs has always been a fundamental goal of computer vision. In this thesis we have developed a hierarchy of tools that cover a wide range of topics with the objective of understanding humans from monocular RGB image: from low level feature point descriptors to high level fashion-aware conditional random fields models. In order to build these high level models it is paramount to have a battery of robust and reliable low and mid level cues. Along these lines, we have proposed two low-level keypoint descriptors: one based on the theory of the heat diffusion on images, and the other that uses a convolutional neural network to learn discriminative image patch representations. We also introduce distinct low-level generative models for representing human pose: in particular we present a discrete model based on a directed acyclic graph and a continuous model that consists of poses clustered on a Riemannian manifold. As mid level cues we propose two 3D human pose estimation algorithms: one that estimates the 3D pose given a noisy 2D estimation, and an approach that simultaneously estimates both the 2D and 3D pose. Finally, we formulate higher level models built upon low and mid level cues for understanding humans from single images. Concretely, we focus on two different tasks in the context of fashion: semantic segmentation of clothing, and predicting the fashionability from images with metadata to ultimately provide fashion advice to the user. For all presented approaches we present extensive results and comparisons against the state-of-the-art and show significant improvements on the entire variety of tasks we tackle.

##### Abstract (translated by Google)
从照片中理解人类一直是计算机视觉的基本目标。在本论文中，我们已经开发了一系列工具，涵盖了广泛的主题，目标是从单眼RGB图像理解人类：从低级特征点描述符到高级时尚感知条件随机场模型。为了建立这些高水平的模型，有一个强大的和可靠的低水平和中等水平线索电池是至关重要的。沿着这些思路，我们提出了两个低级关键点描述符：一个基于图像热扩散理论，另一个使用卷积神经网络来学习区分图像块表示。我们还引入了不同的低层生成模型来表示人的姿态：特别是我们提出了一个基于有向无环图的离散模型和一个由在黎曼流形上聚类的姿态组成的连续模型。作为中等水平线索，我们提出了两种三维人体姿态估计算法：一种是在给定噪声二维估计的情况下估计三维姿态，另一种是同时估计二维和三维姿态的方法。最后，我们制定了更高层次的模型，建立在中低层线索上，用于从单幅图像中了解人类。具体来说，我们关注时尚背景下的两个不同任务：服装的语义分割，以及用元数据预测图像的时尚性，最终为用户提供时尚建议。对于所有提出的方法，我们提出了广泛的结果和比较与最先进的技术，并显示了我们所处理的各种任务的显着改善。

##### URL
[https://arxiv.org/abs/1604.08164](https://arxiv.org/abs/1604.08164)

##### PDF
[https://arxiv.org/pdf/1604.08164](https://arxiv.org/pdf/1604.08164)

