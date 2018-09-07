---
layout: post
title: "Joint Cell Nuclei Detection and Segmentation in Microscopy Images Using 3D Convolutional Networks"
date: 2018-09-06 16:45:07
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
我们提出了一种3D卷积神经网络，可以在共聚焦显微镜图像中同时分割和检测细胞核。镜像这些任务的共同依赖性，我们提出的模型由两个串行组件组成：第一部分计算细胞体的分割，而第二部分识别这些细胞的中心。我们的模型在小鼠腮腺唾液腺干细胞核数据集上从头开始进行端到端训练，该数据集包括来自三个独立细胞制备物的107个图像堆叠，每个细胞制备物包含数百个3D细胞核。在我们的实验中，我们在两个不同的数据集上对检测准确度和分割质量进行了全面评估。结果表明，与现有技术和基准算法相比，所提出的方法提供了显着改进的检测和分割精度。最后，我们使用先前描述的测试时间退出策略来获得我们预测的不确定性估计，并通过证明它们与准确性密切相关来验证这些估计。

##### URL
[http://arxiv.org/abs/1805.02850](http://arxiv.org/abs/1805.02850)

##### PDF
[http://arxiv.org/e-print/1805.02850](http://arxiv.org/e-print/1805.02850)

