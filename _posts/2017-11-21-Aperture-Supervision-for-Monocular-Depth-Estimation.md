---
layout: post
title: "Aperture Supervision for Monocular Depth Estimation"
date: 2017-11-21 17:39:51
categories: arXiv_CV
tags: arXiv_CV
author: Pratul P. Srinivasan, Rahul Garg, Neal Wadhwa, Ren Ng, Jonathan T. Barron
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method to train machine learning algorithms to estimate scene depths from a single image, by using the information provided by a camera's aperture as supervision. Prior works use a depth sensor's outputs or images of the same scene from alternate viewpoints as supervision, while our method instead uses images from the same viewpoint taken with a varying camera aperture. To enable learning algorithms to use aperture effects as supervision, we introduce two differentiable aperture rendering functions that use the input image and predicted depths to simulate the depth-of-field effects caused by real camera apertures. We train a monocular depth estimation network end-to-end to predict the scene depths that best explain these finite aperture images as defocus-blurred renderings of the input all-in-focus image.

##### Abstract (translated by Google)
我们提出了一种新的方法来训练机器学习算法，通过使用由相机的光圈提供的信息作为监督，从单个图像估计场景深度。以前的作品使用深度传感器的输出或交替视点的相同场景的图像作为监督，而我们的方法使用来自相同视角的图像，以不同的相机光圈拍摄。为了使学习算法能够使用光圈效果作为监督，我们引入了两个可微调的光圈渲染函数，它们使用输入图像和预测的深度来模拟实际摄像机光圈引起的景深效应。我们对单目深度估计网络进行端对端训练，以预测最能解释这些有限孔径图像的场景深度，作为输入全焦点图像的散焦模糊渲染。

##### URL
[https://arxiv.org/abs/1711.07933](https://arxiv.org/abs/1711.07933)

##### PDF
[https://arxiv.org/pdf/1711.07933](https://arxiv.org/pdf/1711.07933)

