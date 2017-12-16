---
layout: post
title: "A Deep Cascade of Convolutional Neural Networks for Dynamic MR Image Reconstruction"
date: 2017-11-23 11:28:10
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Relation
author: Jo Schlemper, Jose Caballero, Joseph V. Hajnal, Anthony Price, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by recent advances in deep learning, we propose a framework for reconstructing dynamic sequences of 2D cardiac magnetic resonance (MR) images from undersampled data using a deep cascade of convolutional neural networks (CNNs) to accelerate the data acquisition process. In particular, we address the case where data is acquired using aggressive Cartesian undersampling. Firstly, we show that when each 2D image frame is reconstructed independently, the proposed method outperforms state-of-the-art 2D compressed sensing approaches such as dictionary learning-based MR image reconstruction, in terms of reconstruction error and reconstruction speed. Secondly, when reconstructing the frames of the sequences jointly, we demonstrate that CNNs can learn spatio-temporal correlations efficiently by combining convolution and data sharing approaches. We show that the proposed method consistently outperforms state-of-the-art methods and is capable of preserving anatomical structure more faithfully up to 11-fold undersampling. Moreover, reconstruction is very fast: each complete dynamic sequence can be reconstructed in less than 10s and, for the 2D case, each image frame can be reconstructed in 23ms, enabling real-time applications.

##### Abstract (translated by Google)
受深度学习近期进展的启发，我们提出了一个框架，利用深层级的卷积神经网络（CNN）来重建欠采样数据的二维心脏磁共振（MR）图像的动态序列，以加速数据采集过程。特别是，我们解决了使用积极的笛卡儿（Cartesian）欠采样来获取数据的情况。首先，在重建误差和重构速度方面，本文提出的方法在每个二维图像帧独立重构的情况下，均优于现有的二维压缩感知方法，如基于字典学习的MR图像重建。其次，当联合重构序列帧时，我们证明CNN可以通过卷积和数据共享的方法有效地学习时空相关性。我们表明，提出的方法始终胜过最先进的方法，并能够更忠实地保留解剖结构高达11倍的欠采样。而且，重构速度非常快：每个完整的动态序列可以在不到10秒的时间内完成重构，对于2D的情况，每个图像帧可以在23ms内重建，从而实现实时应用。

##### URL
[https://arxiv.org/abs/1704.02422](https://arxiv.org/abs/1704.02422)

##### PDF
[https://arxiv.org/pdf/1704.02422](https://arxiv.org/pdf/1704.02422)

