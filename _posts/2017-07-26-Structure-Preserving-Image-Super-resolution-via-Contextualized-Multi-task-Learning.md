---
layout: post
title: "Structure-Preserving Image Super-resolution via Contextualized Multi-task Learning"
date: 2017-07-26 09:48:03
categories: arXiv_CV
tags: arXiv_CV Salient Super_Resolution Attention CNN
author: Yukai Shi, Keze Wang, Chongyu Chen, Li Xu, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Single image super resolution (SR), which refers to reconstruct a higher-resolution (HR) image from the observed low-resolution (LR) image, has received substantial attention due to its tremendous application potentials. Despite the breakthroughs of recently proposed SR methods using convolutional neural networks (CNNs), their generated results usually lack of preserving structural (high-frequency) details. In this paper, regarding global boundary context and residual context as complimentary information for enhancing structural details in image restoration, we develop a contextualized multi-task learning framework to address the SR problem. Specifically, our method first extracts convolutional features from the input LR image and applies one deconvolutional module to interpolate the LR feature maps in a content-adaptive way. Then, the resulting feature maps are fed into two branched sub-networks. During the neural network training, one sub-network outputs salient image boundaries and the HR image, and the other sub-network outputs the local residual map, i.e., the residual difference between the generated HR image and ground-truth image. On several standard benchmarks (i.e., Set5, Set14 and BSD200), our extensive evaluations demonstrate the effectiveness of our SR method on achieving both higher restoration quality and computational efficiency compared with several state-of-the-art SR approaches. The source code and some SR results can be found at: this http URL

##### Abstract (translated by Google)
单幅图像超分辨率（SR）是指从观察到的低分辨率（LR）图像中重建高分辨率（HR）图像，由于其巨大的应用潜力而获得了大量的关注。尽管最近提出的使用卷积神经网络（CNN）的SR方法取得了突破性进展，但其产生的结果通常缺乏保留的结构（高频）细节。本文将全局边界背景和残差背景作为增强图像恢复结构细节的补充信息，开发了一个语境化的多任务学习框架来解决SR问题。具体而言，我们的方法首先从输入的LR图像中提取卷积特征，并应用一个去卷积模块以内容自适应的方式内插LR特征映射。然后，得到的特征映射被馈送到两个分支子网络中。在神经网络训练过程中，一个子网络输出显着的图像边界和HR图像，另一个子网络输出局部残差图，即生成的HR图像和地面实况图像之间的残差。在几个标准基准（即Set5，Set14和BSD200）上，我们广泛的评估证明了与一些最先进的SR方法相比，我们的SR方法在实现更高的恢复质量和计算效率方面的有效性。源代码和一些SR结果可以在这个http URL找到

##### URL
[https://arxiv.org/abs/1707.08340](https://arxiv.org/abs/1707.08340)

##### PDF
[https://arxiv.org/pdf/1707.08340](https://arxiv.org/pdf/1707.08340)

