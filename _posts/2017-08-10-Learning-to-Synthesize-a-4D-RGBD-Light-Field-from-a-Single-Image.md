---
layout: post
title: "Learning to Synthesize a 4D RGBD Light Field from a Single Image"
date: 2017-08-10 16:50:29
categories: arXiv_CV
tags: arXiv_CV CNN
author: Pratul P. Srinivasan, Tongzhou Wang, Ashwin Sreelal, Ravi Ramamoorthi, Ren Ng
mathjax: true
---

* content
{:toc}

##### Abstract
We present a machine learning algorithm that takes as input a 2D RGB image and synthesizes a 4D RGBD light field (color and depth of the scene in each ray direction). For training, we introduce the largest public light field dataset, consisting of over 3300 plenoptic camera light fields of scenes containing flowers and plants. Our synthesis pipeline consists of a convolutional neural network (CNN) that estimates scene geometry, a stage that renders a Lambertian light field using that geometry, and a second CNN that predicts occluded rays and non-Lambertian effects. Our algorithm builds on recent view synthesis methods, but is unique in predicting RGBD for each light field ray and improving unsupervised single image depth estimation by enforcing consistency of ray depths that should intersect the same scene point. Please see our supplementary video at this https URL

##### Abstract (translated by Google)
我们提出一种机器学习算法，其将二维RGB图像作为输入并合成四维RGBD光场（每个光线方向上的场景的颜色和深度）。对于培训，我们介绍了最大的公共光场数据集，包括超过3300全景照相机光场的花卉和植物场景。我们的合成流水线包括估计场景几何的卷积神经网络（CNN），使用该几何体渲染朗伯光场的阶段，以及预测遮挡光线和非朗伯效应的第二个CNN。我们的算法建立在最近的视图合成方法上，但是在预测每个光场射线的RGBD方面是独特的，并且通过强化应当与相同场景点相交的射线深度的一致性来改善无监督单图像深度估计。请在此https网址查看我们的补充视频

##### URL
[https://arxiv.org/abs/1708.03292](https://arxiv.org/abs/1708.03292)

##### PDF
[https://arxiv.org/pdf/1708.03292](https://arxiv.org/pdf/1708.03292)

