---
layout: post
title: "iPose: Instance-Aware 6D Pose Estimation of Partly Occluded Objects"
date: 2018-06-18 11:08:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Pose_Estimation Optimization Deep_Learning
author: Omid Hosseini Jafari, Siva Karthik Mustikovela, Karl Pertsch, Eric Brachmann, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
We address the task of 6D pose estimation of known rigid objects from single input images in scenarios where the objects are partly occluded. Recent RGB-D-based methods are robust to moderate degrees of occlusion. For RGB inputs, no previous method works well for partly occluded objects. Our main contribution is to present the first deep learning-based system that estimates accurate poses for partly occluded objects from RGB-D and RGB input. We achieve this with a new instance-aware pipeline that decomposes 6D object pose estimation into a sequence of simpler steps, where each step removes specific aspects of the problem. The first step localizes all known objects in the image using an instance segmentation network, and hence eliminates surrounding clutter and occluders. The second step densely maps pixels to 3D object surface positions, so called object coordinates, using an encoder-decoder network, and hence eliminates object appearance. The third, and final, step predicts the 6D pose using geometric optimization. We demonstrate that we significantly outperform the state-of-the-art for pose estimation of partly occluded objects for both RGB and RGB-D input.

##### Abstract (translated by Google)
我们针对物体被部分遮挡的情况下单个输入图像中已知刚性物体的6D姿态估计的任务。最近基于RGB-D的方法对中等程度的闭塞是稳健的。对于RGB输入，以前的方法对于部分遮挡物体没有效果。我们的主要贡献是提出第一个深度学习型系统，可以估计来自RGB-D和RGB输入的部分遮挡物体的精确位姿。我们通过一种新的实例感知流水线实现了这一点，该流水线将6D对象姿态估计分解为一系列更简单的步骤，其中每个步骤都会消除问题的特定方面。第一步使用实例分割网络定位图像中所有已知对象，从而消除周围的杂乱和遮挡物。第二步使用编码器 - 解码器网络将像素密集地映射到3D对象表面位置，即所谓的对象坐标，并因此消除了对象外观。第三步和最后一步使用几何优化预测6D姿态。我们证明，对于RGB和RGB-D输入的部分遮挡物体的姿态估计，我们显着优于最先进的姿态估计。

##### URL
[http://arxiv.org/abs/1712.01924](http://arxiv.org/abs/1712.01924)

##### PDF
[http://arxiv.org/pdf/1712.01924](http://arxiv.org/pdf/1712.01924)

