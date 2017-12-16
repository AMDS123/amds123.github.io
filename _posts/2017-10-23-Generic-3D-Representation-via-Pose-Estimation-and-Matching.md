---
layout: post
title: "Generic 3D Representation via Pose Estimation and Matching"
date: 2017-10-23 13:01:05
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation
author: Amir R. Zamir, Tilman Wekel, Pulkit Argrawal, Colin Weil, Jitendra Malik, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
Though a large body of computer vision research has investigated developing generic semantic representations, efforts towards developing a similar representation for 3D has been limited. In this paper, we learn a generic 3D representation through solving a set of foundational proxy 3D tasks: object-centric camera pose estimation and wide baseline feature matching. Our method is based upon the premise that by providing supervision over a set of carefully selected foundational tasks, generalization to novel tasks and abstraction capabilities can be achieved. We empirically show that the internal representation of a multi-task ConvNet trained to solve the above core problems generalizes to novel 3D tasks (e.g., scene layout estimation, object pose estimation, surface normal estimation) without the need for fine-tuning and shows traits of abstraction abilities (e.g., cross-modality pose estimation). In the context of the core supervised tasks, we demonstrate our representation achieves state-of-the-art wide baseline feature matching results without requiring apriori rectification (unlike SIFT and the majority of learned features). We also show 6DOF camera pose estimation given a pair local image patches. The accuracy of both supervised tasks come comparable to humans. Finally, we contribute a large-scale dataset composed of object-centric street view scenes along with point correspondences and camera pose information, and conclude with a discussion on the learned representation and open research questions.

##### Abstract (translated by Google)
虽然大量的计算机视觉研究已经研究了开发通用语义表示，但为3D开发类似表示的努力却受到了限制。在本文中，我们通过求解一组基本的代理3D任务来学习一个通用的3D表示：以对象为中心的相机姿态估计和宽基线特征匹配。我们的方法是基于这样的前提：通过对一组精心挑选的基础任务提供监督，可以实现对新任务和抽象能力的推广。我们通过实验证明，为解决上述核心问题而训练的多任务ConvNet的内部表示概括为新颖的3D任务（例如，场景布局估计，对象姿态估计，表面法线估计），而不需要微调和显示特征的抽象能力（例如，跨模态姿态估计）。在核心监督任务的情况下，我们证明我们的表示实现了最先进的宽基线特征匹配结果，而不需要先验整改（不像SIFT和大部分学习功能）。给定一对局部图像块，我们也显示6DOF相机姿态估计。两个监督任务的准确性都与人类相当。最后，我们提供了一个由对象中心街景视图场景组成的大规模数据集以及点对应和摄像机姿态信息，最后讨论了学习表示和开放式研究问题。

##### URL
[https://arxiv.org/abs/1710.08247](https://arxiv.org/abs/1710.08247)

##### PDF
[https://arxiv.org/pdf/1710.08247](https://arxiv.org/pdf/1710.08247)

