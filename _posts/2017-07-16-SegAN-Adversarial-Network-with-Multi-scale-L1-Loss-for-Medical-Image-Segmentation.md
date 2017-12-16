---
layout: post
title: "SegAN: Adversarial Network with Multi-scale $L_1$ Loss for Medical Image Segmentation"
date: 2017-07-16 01:41:03
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Relation
author: Yuan Xue, Tao Xu, Han Zhang, Rodney Long, Xiaolei Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by classic generative adversarial networks (GAN), we propose a novel end-to-end adversarial neural network, called SegAN, for the task of medical image segmentation. Since image segmentation requires dense, pixel-level labeling, the single scalar real/fake output of a classic GAN's discriminator may be ineffective in producing stable and sufficient gradient feedback to the networks. Instead, we use a fully convolutional neural network as the segmentor to generate segmentation label maps, and propose a novel adversarial critic network with a multi-scale $L_1$ loss function to force the critic and segmentor to learn both global and local features that capture long- and short-range spatial relationships between pixels. In our SegAN framework, the segmentor and critic networks are trained in an alternating fashion in a min-max game: The critic takes as input a pair of images, (original_image $*$ predicted_label_map, original_image $*$ ground_truth_label_map), and then is trained by maximizing a multi-scale loss function; The segmentor is trained with only gradients passed along by the critic, with the aim to minimize the multi-scale loss function. We show that such a SegAN framework is more effective and stable for the segmentation task, and it leads to better performance than the state-of-the-art U-net segmentation method. We tested our SegAN method using datasets from the MICCAI BRATS brain tumor segmentation challenge. Extensive experimental results demonstrate the effectiveness of the proposed SegAN with multi-scale loss: on BRATS 2013 SegAN gives performance comparable to the state-of-the-art for whole tumor and tumor core segmentation while achieves better precision and sensitivity for Gd-enhance tumor core segmentation; on BRATS 2015 SegAN achieves better performance than the state-of-the-art in both dice score and precision.

##### Abstract (translated by Google)
受到经典生成对抗网络（GAN）的启发，我们提出了一种新的端到端对抗神经网络，称为SegAN，用于医学图像分割任务。由于图像分割需要密集的像素级标签，经典的GAN鉴别器的单一标量实/伪输出对于产生对网络的稳定和充分的梯度反馈可能是无效的。相反，我们使用完全卷积神经网络作为分割器来生成分割标签映射，并提出了一个具有多尺度$ L_1 $损失函数的新型对抗批评网络，迫使批评者和分割者学习全局和局部特征像素之间的长距离和短距离空间关系。在我们的SegAN框架中，分段器和评论者网络在min-max游戏中以交替方式进行训练：评论者将输入的图像对（original_image $ * $ predicted_label_map，original_image $ * $ ground_truth_label_map）作为输入，然后是通过最大化多尺度损失函数进行训练;这个分割器只是经过批评者传递的渐变训练，其目的是最小化多尺度损失函数。我们证明了这样的一个SegAN框架对于分割任务是更加有效和稳定的，并且导致比现有技术的U网分割方法更好的性能。我们使用来自MICCAI BRATS脑肿瘤分割挑战的数据集测试了我们的SegAN方法。广泛的实验结果证明了所提出的具有多尺度损失的SegAN的有效性：在BRATS 2013上，SegAN具有与全肿瘤和肿瘤核心分割的现有技术相当的性能，同时对Gd-增强肿瘤实现更好的精确度和灵敏度核心分割;在BRATS 2015上，Segan在骰子评分和精确度方面的表现都优于现有技术。

##### URL
[https://arxiv.org/abs/1706.01805](https://arxiv.org/abs/1706.01805)

##### PDF
[https://arxiv.org/pdf/1706.01805](https://arxiv.org/pdf/1706.01805)

