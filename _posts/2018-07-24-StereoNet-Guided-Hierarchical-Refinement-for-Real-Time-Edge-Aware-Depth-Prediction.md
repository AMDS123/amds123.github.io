---
layout: post
title: "StereoNet: Guided Hierarchical Refinement for Real-Time Edge-Aware Depth Prediction"
date: 2018-07-24 00:45:36
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Sameh Khamis, Sean Fanello, Christoph Rhemann, Adarsh Kowdle, Julien Valentin, Shahram Izadi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents StereoNet, the first end-to-end deep architecture for real-time stereo matching that runs at 60 fps on an NVidia Titan X, producing high-quality, edge-preserved, quantization-free disparity maps. A key insight of this paper is that the network achieves a sub-pixel matching precision than is a magnitude higher than those of traditional stereo matching approaches. This allows us to achieve real-time performance by using a very low resolution cost volume that encodes all the information needed to achieve high disparity precision. Spatial precision is achieved by employing a learned edge-aware upsampling function. Our model uses a Siamese network to extract features from the left and right image. A first estimate of the disparity is computed in a very low resolution cost volume, then hierarchically the model re-introduces high-frequency details through a learned upsampling function that uses compact pixel-to-pixel refinement networks. Leveraging color input as a guide, this function is capable of producing high-quality edge-aware output. We achieve compelling results on multiple benchmarks, showing how the proposed method offers extreme flexibility at an acceptable computational budget.

##### Abstract (translated by Google)
本文介绍了StereoNet，这是第一个用于实时立体匹配的端到端深度架构，在NVidia Titan X上以60 fps运行，可生成高质量，边缘保留，无量化的视差图。本文的一个重要见解是网络实现了亚像素匹配精度，而不是传统立体匹配方法的精度。这使我们能够通过使用非常低分辨率的成本量来实现实时性能，该成本量对实现高视差精度所需的所有信息进行编码。通过采用学习的边缘感知上采样功能来实现空间精度。我们的模型使用Siamese网络从左右图像中提取特征。在非常低分辨率的成本体积中计算视差的第一估计，然后分层地通过使用紧凑的像素到像素细化网络的学习的上采样函数来重新引入高频细节。利用颜色输入作为指导，该功能能够产生高质量的边缘感知输出。我们在多个基准测试中获得了令人信服的结果，展示了所提出的方法如何在可接受的计算预算下提供极大的灵

##### URL
[https://arxiv.org/abs/1807.08865](https://arxiv.org/abs/1807.08865)

##### PDF
[https://arxiv.org/pdf/1807.08865](https://arxiv.org/pdf/1807.08865)

