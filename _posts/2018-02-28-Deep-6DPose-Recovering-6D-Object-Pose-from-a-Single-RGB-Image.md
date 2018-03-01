---
layout: post
title: "Deep-6DPose: Recovering 6D Object Pose from a Single RGB Image"
date: 2018-02-28 11:27:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Pose_Estimation Inference Deep_Learning Detection
author: Thanh-Toan Do, Ming Cai, Trung Pham, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting objects and their 6D poses from only RGB images is an important task for many robotic applications. While deep learning methods have made significant progress in visual object detection and segmentation, the object pose estimation task is still challenging. In this paper, we introduce an end-toend deep learning framework, named Deep-6DPose, that jointly detects, segments, and most importantly recovers 6D poses of object instances from a single RGB image. In particular, we extend the recent state-of-the-art instance segmentation network Mask R-CNN with a novel pose estimation branch to directly regress 6D object poses without any post-refinements. Our key technical contribution is the decoupling of pose parameters into translation and rotation so that the rotation can be regressed via a Lie algebra representation. The resulting pose regression loss is differential and unconstrained, making the training tractable. The experiments on two standard pose benchmarking datasets show that our proposed approach compares favorably with the state-of-the-art RGB-based multi-stage pose estimation methods. Importantly, due to the end-to-end architecture, Deep-6DPose is considerably faster than competing multi-stage methods, offers an inference speed of 10 fps that is well suited for robotic applications.

##### Abstract (translated by Google)
仅从RGB图像中检测物体及其6D姿态对许多机器人应用来说是一项重要任务。尽管深度学习方法在视觉对象检测和分割方面取得了重大进展，但对象姿态估计任务仍然具有挑战性。在本文中，我们介绍了一个名为Deep-6DPose的端到端深度学习框架，它共同检测，分段并最重要地从单个RGB图像中恢复对象实例的6D姿态。特别是，我们使用一种新颖的姿态估计分支来扩展最近的最新的实例分割网络Mask R-CNN，以直接对6D对象姿态进行无需任何后期改进。我们的主要技术贡献是将姿态参数解耦为平移和旋转，以便旋转可以通过李代数表示进行回归。由此产生的姿态回归损失是有差别的，不受限制的，这使得训练易于处理。在两个标准姿态基准数据集上的实验表明，我们提出的方法与基于RGB的多阶段姿态估计方法相比有优势。重要的是，由于端到端的架构，Deep-6DPose比竞争的多阶段方法快得多，提供了10fps的推理速度，非常适合机器人应用。

##### URL
[http://arxiv.org/abs/1802.10367](http://arxiv.org/abs/1802.10367)

##### PDF
[http://arxiv.org/pdf/1802.10367](http://arxiv.org/pdf/1802.10367)

