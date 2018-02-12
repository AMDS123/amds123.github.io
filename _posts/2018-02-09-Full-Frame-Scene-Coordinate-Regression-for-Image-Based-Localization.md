---
layout: post
title: "Full-Frame Scene Coordinate Regression for Image-Based Localization"
date: 2018-02-09 12:55:30
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Prediction
author: Xiaotian Li, Juha Ylioinas, Juho Kannala
mathjax: true
---

* content
{:toc}

##### Abstract
Image-based localization, or camera relocalization, is a fundamental problem in computer vision and robotics, and it refers to estimating camera pose from an image. Recent state-of-the-art approaches use learning based methods, such as Random Forests (RFs) and Convolutional Neural Networks (CNNs), to regress for each pixel in the image its corresponding position in the scene's world coordinate frame, and solve the final pose via a RANSAC-based optimization scheme using the predicted correspondences. In this paper, instead of in a patch-based manner, we propose to perform the scene coordinate regression in a full-frame manner to make the computation efficient at test time and, more importantly, to add more global context to the regression process to improve the robustness. To do so, we adopt a fully convolutional encoder-decoder neural network architecture which accepts a whole image as input and produces scene coordinate predictions for all pixels in the image. However, using more global context is prone to overfitting. To alleviate this issue, we propose to use data augmentation to generate more data for training. In addition to the data augmentation in 2D image space, we also augment the data in 3D space. We evaluate our approach on the publicly available 7-Scenes dataset, and experiments show that it has better scene coordinate predictions and achieves state-of-the-art results in localization with improved robustness on the hardest frames (e.g., frames with repeated structures).

##### Abstract (translated by Google)
基于图像的定位或相机重定位是计算机视觉和机器人技术中的一个基本问题，它涉及从图像估计相机姿态。最近的最先进的方法使用基于学习的方法，例如随机森林（RF）和卷积神经网络（CNN）来对图像中的每个像素回归其在场景的世界坐标框架中的对应位置，并且解决使用预测的对应关系通过基于RANSAC的优化方案进行最终姿态。在本文中，我们建议以全帧方式执行场景坐标回归，而不是以补丁为基础的方式进行场景坐标回归，以使测试时的计算效率更高，更重要的是为回归过程添加更多全局上下文提高鲁棒性。为此，我们采用完全卷积编码器 - 解码器神经网络架构，其接受整个图像作为输入，并为图像中的所有像素产生场景坐标预测。但是，使用更多的全局上下文容易出现过度拟合。为了缓解这个问题，我们建议使用数据增加来生成更多的训练数据。除了二维图像空间中的数据增强之外，我们还增加了三维空间中的数据。我们在公开可用的7-Scenes数据集上评估我们的方法，并且实验表明它具有更好的场景坐标预测，并实现了最先进的定位结果，同时改善了最困难帧（例如，具有重复结构的帧） 。

##### URL
[http://arxiv.org/abs/1802.03237](http://arxiv.org/abs/1802.03237)

##### PDF
[http://arxiv.org/pdf/1802.03237](http://arxiv.org/pdf/1802.03237)

