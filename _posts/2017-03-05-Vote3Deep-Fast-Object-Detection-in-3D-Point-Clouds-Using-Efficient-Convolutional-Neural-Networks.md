---
layout: post
title: "Vote3Deep: Fast Object Detection in 3D Point Clouds Using Efficient Convolutional Neural Networks"
date: 2017-03-05 15:29:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Knowledge CNN Detection
author: Martin Engelcke, Dushyant Rao, Dominic Zeng Wang, Chi Hay Tong, Ingmar Posner
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a computationally efficient approach to detecting objects natively in 3D point clouds using convolutional neural networks (CNNs). In particular, this is achieved by leveraging a feature-centric voting scheme to implement novel convolutional layers which explicitly exploit the sparsity encountered in the input. To this end, we examine the trade-off between accuracy and speed for different architectures and additionally propose to use an L1 penalty on the filter activations to further encourage sparsity in the intermediate representations. To the best of our knowledge, this is the first work to propose sparse convolutional layers and L1 regularisation for efficient large-scale processing of 3D data. We demonstrate the efficacy of our approach on the KITTI object detection benchmark and show that Vote3Deep models with as few as three layers outperform the previous state of the art in both laser and laser-vision based approaches by margins of up to 40% while remaining highly competitive in terms of processing time.

##### Abstract (translated by Google)
本文提出了一种使用卷积神经网络（CNN）在三维点云中本地检测物体的计算高效的方法。具体来说，这是通过利用以特征为中心的投票方​​案来实现新颖的卷积层，其明确地利用输入中遇到的稀疏性。为此，我们研究了不同体系结构的精度和速度之间的平衡，并且还建议在过滤器激活上使用L1惩罚来进一步鼓励中间表示中的稀疏性。据我们所知，这是第一个提出稀疏卷积层和L1正则化的高效大规模3D数据处理的工作。我们展示了我们的方法在KITTI物体检测基准测试中的功效，并显示仅有三层的Vote3Deep模型在基于激光和激光视觉的方法中的表现优于先前的技术水平，边缘高达40％，同时保持高度在处理时间方面具有竞争力。

##### URL
[https://arxiv.org/abs/1609.06666](https://arxiv.org/abs/1609.06666)

##### PDF
[https://arxiv.org/pdf/1609.06666](https://arxiv.org/pdf/1609.06666)

