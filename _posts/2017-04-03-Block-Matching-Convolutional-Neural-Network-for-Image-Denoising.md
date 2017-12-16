---
layout: post
title: "Block-Matching Convolutional Neural Network for Image Denoising"
date: 2017-04-03 11:01:47
categories: arXiv_CV
tags: arXiv_CV CNN
author: Byeongyong Ahn, Nam Ik Cho
mathjax: true
---

* content
{:toc}

##### Abstract
There are two main streams in up-to-date image denoising algorithms: non-local self similarity (NSS) prior based methods and convolutional neural network (CNN) based methods. The NSS based methods are favorable on images with regular and repetitive patterns while the CNN based methods perform better on irregular structures. In this paper, we propose a block-matching convolutional neural network (BMCNN) method that combines NSS prior and CNN. Initially, similar local patches in the input image are integrated into a 3D block. In order to prevent the noise from messing up the block matching, we first apply an existing denoising algorithm on the noisy image. The denoised image is employed as a pilot signal for the block matching, and then denoising function for the block is learned by a CNN structure. Experimental results show that the proposed BMCNN algorithm achieves state-of-the-art performance. In detail, BMCNN can restore both repetitive and irregular structures.

##### Abstract (translated by Google)
在最新的图像去噪算法中有两个主流：基于非局部自相似性（NSS）的方法和基于卷积神经网络（CNN）的方法。基于NSS的方法对于具有规则和重复模式的图像是有利的，而基于CNN的方法在不规则结构上表现更好。本文提出了一种将NSS先验和CNN相结合的块匹配卷积神经网络（BMCNN）方法。最初，输入图像中类似的局部块被集成到3D块中。为了防止噪声扰乱块匹配，我们首先在噪声图像上应用现有的去噪算法。采用去噪图像作为块匹配的导频信号，然后利用CNN结构学习块的去噪函数。实验结果表明，提出的BMCNN算法达到了最先进的性能。详细地说，BMCNN可以恢复重复和不规则的结构。

##### URL
[https://arxiv.org/abs/1704.00524](https://arxiv.org/abs/1704.00524)

##### PDF
[https://arxiv.org/pdf/1704.00524](https://arxiv.org/pdf/1704.00524)

