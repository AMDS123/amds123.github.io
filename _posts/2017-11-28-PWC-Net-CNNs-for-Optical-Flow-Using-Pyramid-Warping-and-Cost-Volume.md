---
layout: post
title: "PWC-Net: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume"
date: 2017-11-28 15:52:03
categories: arXiv_CV
tags: arXiv_CV
author: Deqing Sun, Xiaodong Yang, Ming-Yu Liu, Jan Kautz
mathjax: true
---

* content
{:toc}

##### Abstract
We present a compact but effective CNN model for optical flow, called PWC-Net. PWC-Net has been designed according to simple and well-established principles: pyramidal processing, warping, and the use of a cost volume. Cast in a learnable feature pyramid, PWC-Net uses the current optical flow estimate to warp the CNN features of the second image. It then uses the warped features and features of the first image to construct the cost volume, which is processed by a CNN to estimate the optical flow. PWCNet is 17 times smaller in size and easier to train than the recent FlowNet2 model. Moreover, it outperforms all published methods on the MPI Sintel final pass and KITTI 2015 benchmarks, running at about 35 fps on Sintel resolution (1024x436) images. Our model will be publicly available.

##### Abstract (translated by Google)
我们提出了一种紧凑而有效的光纤流量CNN模型，称为PWC-Net。 PWC-Net的设计是按照简单和完善的原则进行的：金字塔形加工，翘曲和成本的使用。在可学习的特征金字塔中，PWC-Net使用当前的光流估计扭曲第二图像的CNN特征。然后使用第一幅图像的变形特征和特征来构造成本体积，由CNN处理以估计光流。 PWCNet的尺寸比最新的FlowNet2型小17倍，且更容易培训。此外，它在Sintel分辨率（1024x436）图像上的性能优于MPI Sintel最终通过和KITTI 2015基准测试的所有已发布方法，速度约为35 fps。我们的模型将公开可用。

##### URL
[https://arxiv.org/abs/1709.02371](https://arxiv.org/abs/1709.02371)

##### PDF
[https://arxiv.org/pdf/1709.02371](https://arxiv.org/pdf/1709.02371)

