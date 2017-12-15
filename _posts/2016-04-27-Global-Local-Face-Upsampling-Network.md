---
layout: post
title: "Global-Local Face Upsampling Network"
date: 2016-04-27 15:31:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution Face
author: Oncel Tuzel, Yuichi Taguchi, John R. Hershey
mathjax: true
---

* content
{:toc}

##### Abstract
Face hallucination, which is the task of generating a high-resolution face image from a low-resolution input image, is a well-studied problem that is useful in widespread application areas. Face hallucination is particularly challenging when the input face resolution is very low (e.g., 10 x 12 pixels) and/or the image is captured in an uncontrolled setting with large pose and illumination variations. In this paper, we revisit the algorithm introduced in [1] and present a deep interpretation of this framework that achieves state-of-the-art under such challenging scenarios. In our deep network architecture the global and local constraints that define a face can be efficiently modeled and learned end-to-end using training data. Conceptually our network design can be partitioned into two sub-networks: the first one implements the holistic face reconstruction according to global constraints, and the second one enhances face-specific details and enforces local patch statistics. We optimize the deep network using a new loss function for super-resolution that combines reconstruction error with a learned face quality measure in adversarial setting, producing improved visual results. We conduct extensive experiments in both controlled and uncontrolled setups and show that our algorithm improves the state of the art both numerically and visually.

##### Abstract (translated by Google)
脸部幻觉是从低分辨率的输入图像生成高分辨率的脸部图像的任务，是一个在广泛的应用领域中有用的深入研究的问题。当输入脸部分辨率非常低（例如，10×12像素）和/或在具有大的姿势和照度变化的不受控制的设置中拍摄图像时，面部幻觉尤其具有挑战性。在本文中，我们重新回顾了文献[1]中介绍的算法，并对这种框架进行了深入的解释，在这种具有挑战性的情况下实现了最新的技术。在我们的深层网络体系结构中，定义人脸的全局和局部约束可以使用训练数据进行有效建模和端对端学习。从概念上讲，我们的网络设计可以划分为两个子网络：第一个是根据全局约束实现整体人脸重建，第二个是加强人脸特定的细节，并执行本地补丁统计。我们使用一种新的超分辨率损失函数优化深度网络，将重建误差与对抗设置中的学习脸部质量测量相结合，产生更好的视觉效果。我们在受控和非受控的设置中进行了广泛的实验，并显示我们的算法在数字和视觉上改进了现有技术。

##### URL
[https://arxiv.org/abs/1603.07235](https://arxiv.org/abs/1603.07235)

##### PDF
[https://arxiv.org/pdf/1603.07235](https://arxiv.org/pdf/1603.07235)

