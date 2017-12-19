---
layout: post
title: "Combining Local Appearance and Holistic View: Dual-Source Deep Neural Networks for Human Pose Estimation"
date: 2015-04-27 17:00:30
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection
author: Xiaochuan Fan, Kang Zheng, Yuewei Lin, Song Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new learning-based method for estimating 2D human pose from a single image, using Dual-Source Deep Convolutional Neural Networks (DS-CNN). Recently, many methods have been developed to estimate human pose by using pose priors that are estimated from physiologically inspired graphical models or learned from a holistic perspective. In this paper, we propose to integrate both the local (body) part appearance and the holistic view of each local part for more accurate human pose estimation. Specifically, the proposed DS-CNN takes a set of image patches (category-independent object proposals for training and multi-scale sliding windows for testing) as the input and then learns the appearance of each local part by considering their holistic views in the full body. Using DS-CNN, we achieve both joint detection, which determines whether an image patch contains a body joint, and joint localization, which finds the exact location of the joint in the image patch. Finally, we develop an algorithm to combine these joint detection/localization results from all the image patches for estimating the human pose. The experimental results show the effectiveness of the proposed method by comparing to the state-of-the-art human-pose estimation methods based on pose priors that are estimated from physiologically inspired graphical models or learned from a holistic perspective.

##### Abstract (translated by Google)
我们提出了一种新的基于学习的方法，使用双源深度卷积神经网络（DS-CNN）从单个图像估计2D人体姿态。最近，已经开发了许多方法来通过使用从生理启发的图形模型估计的或从整体角度学习的姿势先验来估计人体姿势。在本文中，我们建议整合局部（身体）部分外观和每个局部部分的整体视图，以便更准确地进行人体姿态估计。具体来说，所提出的DS-CNN将一组图像块（用于训练的类别无关的对象提议和用于测试的多尺度滑动窗口）作为输入，然后通过考虑它们的整体视图来学习每个本地部分的外观身体。使用DS-CNN，我们实现联合检测，联合检测确定图像块是否包含身体关节，联合定位是发现图像块中关节的确切位置。最后，我们开发了一种算法来结合这些来自所有图像块的联合检测/定位结果来估计人的姿势。实验结果通过与基于先验姿势估计方法的现有技术的人体估计方法进行比较，显示了所提出的方法的有效性，所述方法基于从生理启发的图形模型估计的或从整体角度学习的姿势先验。

##### URL
[https://arxiv.org/abs/1504.07159](https://arxiv.org/abs/1504.07159)

##### PDF
[https://arxiv.org/pdf/1504.07159](https://arxiv.org/pdf/1504.07159)

