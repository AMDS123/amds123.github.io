---
layout: post
title: "Unsupervised CNN for Single View Depth Estimation: Geometry to the Rescue"
date: 2016-07-29 03:20:46
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ravi Garg, Vijay Kumar BG, Gustavo Carneiro, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
A significant weakness of most current deep Convolutional Neural Networks is the need to train them using vast amounts of manu- ally labelled data. In this work we propose a unsupervised framework to learn a deep convolutional neural network for single view depth predic- tion, without requiring a pre-training stage or annotated ground truth depths. We achieve this by training the network in a manner analogous to an autoencoder. At training time we consider a pair of images, source and target, with small, known camera motion between the two such as a stereo pair. We train the convolutional encoder for the task of predicting the depth map for the source image. To do so, we explicitly generate an inverse warp of the target image using the predicted depth and known inter-view displacement, to reconstruct the source image; the photomet- ric error in the reconstruction is the reconstruction loss for the encoder. The acquisition of this training data is considerably simpler than for equivalent systems, requiring no manual annotation, nor calibration of depth sensor to camera. We show that our network trained on less than half of the KITTI dataset (without any further augmentation) gives com- parable performance to that of the state of art supervised methods for single view depth estimation.

##### Abstract (translated by Google)
目前大多数深度卷积神经网络的一个显着弱点是需要使用大量手工标记的数据来训练它们。在这项工作中，我们提出了一个无监督的框架来学习深度卷积神经网络单视点深度预测，而不需要预训练阶段或注释的地面真实深度。我们通过类似于自动编码器的方式训练网络来实现这一点。在训练时，我们考虑一对图像，来源和目标，在两者之间有一个小的，已知的相机运动，例如立体声对。我们训练卷积编码器来预测源图像的深度图。为此，我们使用预测的深度和已知的视点间位移来显式地生成目标图像的反向翘曲，以重建源图像;重建中的光度误差就是编码器的重建损耗。这种训练数据的采集比等效系统简单得多，不需要手动注释，也不需要对深度传感器进行相机校准。我们表明，我们的网络训练不到KITTI数据集的一半（没有任何进一步的增强），与单一视点深度估计的监督状态方法相比，性能相当。

##### URL
[https://arxiv.org/abs/1603.04992](https://arxiv.org/abs/1603.04992)

##### PDF
[https://arxiv.org/pdf/1603.04992](https://arxiv.org/pdf/1603.04992)

