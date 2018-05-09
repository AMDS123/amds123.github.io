---
layout: post
title: "Joint Cell Nuclei Detection and Segmentation in Microscopy Images Using 3D Convolutional Networks"
date: 2018-05-08 06:15:33
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction Detection
author: Sundaresh Ram, Vicky T. Nguyen, Kirsten H. Limesand, Mert R. Sabuncu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a 3D convolutional neural network to simultaneously segment and detect cell nuclei in confocal microscopy images. Mirroring the co-dependency of these tasks, our proposed model consists of two serial components: the first part computes a segmentation of cell bodies, while the second module identifies the centers of these cells. Our model is trained end-to-end from scratch on a mouse parotid salivary gland stem cell nuclei dataset comprising 107 image stacks from three independent cell preparations, each containing several hundred individual cell nuclei in 3D. In our experiments, we conduct a thorough evaluation of both detection accuracy and segmentation quality, on two different datasets. The results show that the proposed method provides significantly improved detection and segmentation accuracy compared to state-of-the-art and benchmark algorithms. Finally, we use a previously described test-time drop-out strategy to obtain uncertainty estimates on our predictions and validate these estimates by demonstrating that they are strongly correlated with accuracy.

##### Abstract (translated by Google)
我们提出了一个三维卷积神经网络来同时分割和检测共聚焦显微图像中的细胞核。镜像这些任务的共依赖性，我们提出的模型由两个串行组件组成：第一部分计算细胞体的分割，而第二部分识别这些细胞的中心。我们的模型是从头开始对小鼠腮腺唾液腺干细胞核数据集进行端对端培训，其中包含来自三种独立细胞制剂的107个图像堆叠，每个细胞制剂包含数百个3D单个细胞核。在我们的实验中，我们对两个不同的数据集进行了检测精度和分割质量的全面评估。结果表明，与现有技术和基准算法相比，所提出的方法提供显着改善的检测和分割准确性。最后，我们使用之前描述的测试时间辍学策略来获得我们预测的不确定性估计值，并通过证明这些估计值与准确性强相关来验证这些估计值。

##### URL
[https://arxiv.org/abs/1805.02850](https://arxiv.org/abs/1805.02850)

##### PDF
[https://arxiv.org/pdf/1805.02850](https://arxiv.org/pdf/1805.02850)

