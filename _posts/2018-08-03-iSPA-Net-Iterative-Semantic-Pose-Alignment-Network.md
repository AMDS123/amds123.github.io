---
layout: post
title: "iSPA-Net: Iterative Semantic Pose Alignment Network"
date: 2018-08-03 09:44:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation Classification
author: Jogendra Nath Kundu, Aditya Ganeshan, Rahul M. V., Aditya Prakash, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding and extracting 3D information of objects from monocular 2D images is a fundamental problem in computer vision. In the task of 3D object pose estimation, recent data driven deep neural network based approaches suffer from scarcity of real images with 3D keypoint and pose annotations. Drawing inspiration from human cognition, where the annotators use a 3D CAD model as structural reference to acquire ground-truth viewpoints for real images; we propose an iterative Semantic Pose Alignment Network, called iSPA-Net. Our approach focuses on exploiting semantic 3D structural regularity to solve the task of fine-grained pose estimation by predicting viewpoint difference between a given pair of images. Such image comparison based approach also alleviates the problem of data scarcity and hence enhances scalability of the proposed approach for novel object categories with minimal annotation. The fine-grained object pose estimator is also aided by correspondence of learned spatial descriptor of the input image pair. The proposed pose alignment framework enjoys the faculty to refine its initial pose estimation in consecutive iterations by utilizing an online rendering setup along with effectiveness of a non-uniform bin classification of pose-difference. This enables iSPA-Net to achieve state-of-the-art performance on various real image viewpoint estimation datasets. Further, we demonstrate effectiveness of the approach for multiple applications. First, we show results for active object viewpoint localization to capture images from similar pose considering only a single image as pose reference. Second, we demonstrate the ability of the learned semantic correspondence to perform unsupervised part-segmentation transfer using only a single part-annotated 3D template model per object class. To encourage reproducible research, we have released the codes for our proposed algorithm.

##### Abstract (translated by Google)
从单眼2D图像中理解和提取物体的3D信息是计算机视觉中的基本问题。在3D对象姿态估计的任务中，基于最近数据驱动的基于深度神经网络的方法遭受具有3D关键点和姿势注释的真实图像的稀缺性。从人类认知中汲取灵感，其中注释者使用3D CAD模型作为结构参考来获取真实图像的地面真实观点;我们提出了一个迭代的语义姿势对齐网络，称为iSPA-Net。我们的方法侧重于利用语义3D结构规律性来通过预测给定图像对之间的视点差异来解决细粒度姿态估计的任务。这种基于图像比较的方法还减轻了数据稀缺的问题，并因此增强了所提出的方法的可扩展性，用于具有最小注释的新对象类别。细粒度对象姿势估计器还通过输入图像对的学习空间描述符的对应来辅助。所提出的姿势对齐框架通过利用在线渲染设置以及姿势差的非均匀bin分类的有效性，享有在连续迭代中改进其初始姿态估计的能力。这使iSPA-Net能够在各种真实图像视点估计数据集上实现最先进的性能。此外，我们证明了该方法对多种应用的有效性。首先，我们显示活动对象视点定位的结果，以仅考虑单个图像作为姿势参考来捕获来自相似姿势的图像。其次，我们展示了学习语义对应的能力，即每个对象类仅使用单个部分注​​释的3D模板模型来执行无监督的部分分割传递。为了鼓励可重复的研究，我们已经发布了我们提出的算法的代码。

##### URL
[http://arxiv.org/abs/1808.01134](http://arxiv.org/abs/1808.01134)

##### PDF
[http://arxiv.org/pdf/1808.01134](http://arxiv.org/pdf/1808.01134)

