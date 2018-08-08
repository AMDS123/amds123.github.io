---
layout: post
title: "Non-Learning based Deep Parallel MRI Reconstruction"
date: 2018-08-06 21:26:06
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning
author: Ali Pour Yazdanpanah, Onur Afacan, Simon K. Warfield
mathjax: true
---

* content
{:toc}

##### Abstract
Fast data acquisition in Magnetic Resonance Imaging (MRI) is vastly in demand and scan time directly depends on the number of acquired k-space samples. The most common issues in any deep learning-based MRI reconstruction approaches are generalizability and transferability. For different MRI scanner configurations using these approaches, the network must be trained from scratch every time with new training dataset, acquired under new configurations, to be able to provide good reconstruction performance. Here, we propose a new parallel imaging method based on deep neural networks called NLDpMRI to reduce any structured aliasing ambiguities related to the different k-space undersampling patterns for accelerated data acquisition. Two loss functions including non-regularized and regularized are proposed for parallel MRI reconstruction using deep network optimization and we reconstruct MR images by optimizing the proposed loss functions over the network parameters. Unlike any deep learning-based MRI reconstruction approaches, our method doesn't include any training step that the network learns from a large number of training samples and it only needs the single undersampled multi-coil k-space data for reconstruction. Also, the proposed method can handle k-space data with different undersampling patterns, and different number of coils. Unlike most deep learning-based MRI reconstruction methods, our method operates on real-world acquisitions with the complex data format, not on simulated data, real-valued data, or data with added simulated-phase. Experimental results show that the proposed method outperforms the current state-of-the-art GRAPPA reconstruction method.

##### Abstract (translated by Google)
磁共振成像（MRI）中的快速数据采集非常需要，扫描时间直接取决于采集的k空间样本的数量。任何基于深度学习的MRI重建方法中最常见的问题是普遍性和可转移性。对于使用这些方法的不同MRI扫描仪配置，必须每次使用新配置下获得的新训练数据集从头开始训练网络，以便能够提供良好的重建性能。在这里，我们提出了一种新的基于深度神经网络的并行成像方法，称为NLDpMRI，以减少与加速数据采集的不同k空间欠采样模式相关的任何结构化混叠模糊。提出了两种损失函数，包括非正则化和正则化，用于使用深度网络优化的并行MRI重建，并且我们通过优化所提出的网络参数上的损失函数来重建MR图像。与任何基于深度学习的MRI重建方法不同，我们的方法不包括网络从大量训练样本中学习的任何训练步骤，并且它仅需要单个欠采样多线圈k空间数据用于重建。而且，所提出的方法可以处理具有不同欠采样模式和不同数量的线圈的k空间数据。与大多数基于深度学习的MRI重建方法不同，我们的方法使用复杂数据格式进行实际采集，而不是模拟数据，实值数据或添加模拟相位的数据。实验结果表明，该方法优于目前最先进的GRAPPA重建方法。

##### URL
[http://arxiv.org/abs/1808.02122](http://arxiv.org/abs/1808.02122)

##### PDF
[http://arxiv.org/pdf/1808.02122](http://arxiv.org/pdf/1808.02122)

