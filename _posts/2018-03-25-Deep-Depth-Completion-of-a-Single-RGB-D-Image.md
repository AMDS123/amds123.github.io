---
layout: post
title: "Deep Depth Completion of a Single RGB-D Image"
date: 2018-03-25 20:07:10
categories: arXiv_CV
tags: arXiv_CV Face Optimization Prediction
author: Yinda Zhang, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of our work is to complete the depth channel of an RGB-D image. Commodity-grade depth cameras often fail to sense depth for shiny, bright, transparent, and distant surfaces. To address this problem, we train a deep network that takes an RGB image as input and predicts dense surface normals and occlusion boundaries. Those predictions are then combined with raw depth observations provided by the RGB-D camera to solve for depths for all pixels, including those missing in the original observation. This method was chosen over others (e.g., inpainting depths directly) as the result of extensive experiments with a new depth completion benchmark dataset, where holes are filled in training data through the rendering of surface reconstructions created from multiview RGB-D scans. Experiments with different network inputs, depth representations, loss functions, optimization methods, inpainting methods, and deep depth estimation networks show that our proposed approach provides better depth completions than these alternatives.

##### Abstract (translated by Google)
我们的工作目标是完成RGB-D图像的深度通道。商品级深度摄像机通常无法感知有光泽，明亮，透明和远处表面的深度。为了解决这个问题，我们训练一个深度网络，将RGB图像作为输入，并预测密集的表面法线和遮挡边界。然后将这些预测与由RGB-D相机提供的原始深度观测相结合，以求解所有像素的深度，包括原始观测中缺失的那些像素。作为使用新的深度完成基准数据集进行大量实验的结果，该方法被选择为其他方法（例如，直接修复深度），其中通过渲染由多视图RGB-D扫描创建的表面重建来填充训练数据中的空洞。不同网络输入，深度表示，损失函数，优化方法，修补方法和深度估计网络的实验表明，我们提出的方法提供了比这些替代方案更好的深度完成。

##### URL
[https://arxiv.org/abs/1803.09326](https://arxiv.org/abs/1803.09326)

##### PDF
[https://arxiv.org/pdf/1803.09326](https://arxiv.org/pdf/1803.09326)

