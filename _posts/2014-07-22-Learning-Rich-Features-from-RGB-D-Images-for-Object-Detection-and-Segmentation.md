---
layout: post
title: "Learning Rich Features from RGB-D Images for Object Detection and Segmentation"
date: 2014-07-22 05:31:32
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Saurabh Gupta, Ross Girshick, Pablo Arbeláez, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we study the problem of object detection for RGB-D images using semantically rich image and depth features. We propose a new geocentric embedding for depth images that encodes height above ground and angle with gravity for each pixel in addition to the horizontal disparity. We demonstrate that this geocentric embedding works better than using raw depth images for learning feature representations with convolutional neural networks. Our final object detection system achieves an average precision of 37.3%, which is a 56% relative improvement over existing methods. We then focus on the task of instance segmentation where we label pixels belonging to object instances found by our detector. For this task, we propose a decision forest approach that classifies pixels in the detection window as foreground or background using a family of unary and binary tests that query shape and geocentric pose features. Finally, we use the output from our object detectors in an existing superpixel classification framework for semantic scene segmentation and achieve a 24% relative improvement over current state-of-the-art for the object categories that we study. We believe advances such as those represented in this paper will facilitate the use of perception in fields like robotics.

##### Abstract (translated by Google)
在本文中，我们使用语义丰富的图像和深度特征来研究RGB-D图像的对象检测问题。我们提出了一种新的地心深度图像嵌入技术，除水平像差外，还对每个像素编码地面高度和重力角度。我们证明，这种地心中的嵌入效果比使用卷积神经网络学习特征表示的原始深度图像更好。我们的最终目标检测系统的平均精度达到了37.3％，比现有方法提高了56％。然后，我们将重点放在实例分割的任务上，在该分割中我们标记属于我们的检测器找到的对象实例对于这个任务，我们提出了一种决策森林方法，使用查询形状和地心坐标特征的一元和二元测试族将在检测窗口中的像素分类为前景或背景。最后，我们将现有的超像素分类框架中的物体检测器的输出结果用于语义场景分割，对于我们所研究的对象类别，实现了比现有技术水平高出24％的相对改进。我们相信本文中所介绍的进步将有助于在机器人领域使用感知。

##### URL
[https://arxiv.org/abs/1407.5736](https://arxiv.org/abs/1407.5736)

