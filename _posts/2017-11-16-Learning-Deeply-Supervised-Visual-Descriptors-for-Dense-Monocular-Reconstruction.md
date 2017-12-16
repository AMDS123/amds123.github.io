---
layout: post
title: "Learning Deeply Supervised Visual Descriptors for Dense Monocular Reconstruction"
date: 2017-11-16 04:22:49
categories: arXiv_CV
tags: arXiv_CV Sparse CNN SLAM
author: Chamara Saroj Weerasekera, Ravi Garg, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Visual SLAM (Simultaneous Localization and Mapping) methods typically rely on handcrafted visual features or raw RGB values for establishing correspondences between images. These features, while suitable for sparse mapping, often lead to ambiguous matches at texture-less regions when performing dense reconstruction due to the aperture problem. In this work, we explore the use of learned features for the matching task in dense monocular reconstruction. We propose a novel convolutional neural network (CNN) architecture along with a deeply supervised feature learning scheme for pixel-wise regression of visual descriptors from an image which are best suited for dense monocular SLAM. In particular, our learning scheme minimizes a multi-view matching cost-volume loss with respect to the regressed features at multiple stages within the network, for explicitly learning contextual features that are suitable for dense matching between images captured by a moving monocular camera along the epipolar line. We utilize the learned features from our model for depth estimation inside a real-time dense monocular SLAM framework, where photometric error is replaced by our learned descriptor error. Our evaluation on several challenging indoor scenes demonstrate greatly improved accuracy in dense reconstructions of the well celebrated dense SLAM systems like DTAM, without compromising their real-time performance.

##### Abstract (translated by Google)
视觉SLAM（同时定位和映射）方法通常依靠手工制作的视觉特征或原始RGB值来建立图像之间的对应关系。这些特征虽然适用于稀疏映射，但在由于孔径问题进行密集重建时，通常会导致无纹理区域的模糊匹配。在这项工作中，我们探索使用学习功能的匹配任务在重建单眼重建。我们提出了一种新颖的卷积神经网络（CNN）架构，以及深度监督的特征学习方案，用于从最适合于致密单眼SLAM的图像中进行视觉描述符的像素回归。具体而言，我们的学习方案最大限度地减少了与网络内多个阶段的退化特征有关的多视图匹配的成本 - 体积损失，用于明确地学习适合于沿着移动单目照相机捕获的图像之间的密集匹配的上下文特征核线。我们利用我们模型的学习特征在实时密集单目SLAM框架内进行深度估计，其中光度误差由我们学习的描述符误差代替。我们对几个具有挑战性的室内场景的评估表明，在密集重建像DTAM这样着名的密集SLAM系统时，其精度大大提高，而且不会影响其实时性能。

##### URL
[https://arxiv.org/abs/1711.05919](https://arxiv.org/abs/1711.05919)

##### PDF
[https://arxiv.org/pdf/1711.05919](https://arxiv.org/pdf/1711.05919)

