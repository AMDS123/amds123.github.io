---
layout: post
title: "A Self-supervised Learning System for Object Detection using Physics Simulation and Multi-view Pose Estimation"
date: 2017-08-03 15:04:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Chaitanya Mitash, Kostas E. Bekris, Abdeslam Boularias
mathjax: true
---

* content
{:toc}

##### Abstract
Progress has been achieved recently in object detection given advancements in deep learning. Nevertheless, such tools typically require a large amount of training data and significant manual effort to label objects. This limits their applicability in robotics, where solutions must scale to a large number of objects and variety of conditions. This work proposes an autonomous process for training a Convolutional Neural Network (CNN) for object detection and pose estimation in robotic setups. The focus is on detecting objects placed in cluttered, tight environments, such as a shelf with multiple objects. In particular, given access to 3D object models, several aspects of the environment are physically simulated. The models are placed in physically realistic poses with respect to their environment to generate a labeled synthetic dataset. To further improve object detection, the network self-trains over real images that are labeled using a robust multi-view pose estimation process. The proposed training process is evaluated on several existing datasets and on a dataset collected for this paper with a Motoman robotic arm. Results show that the proposed approach outperforms popular training processes relying on synthetic - but not physically realistic - data and manual annotation. The key contributions are the incorporation of physical reasoning in the synthetic data generation process and the automation of the annotation process over real images.

##### Abstract (translated by Google)
随着深度学习的进展，最近在物体检测方面取得了进展。尽管如此，这些工具通常需要大量的训练数据和大量的人力来标记对象。这限制了它们在机器人领域的适用性，其中解决方案必须扩展到大量的对象和各种条件。这项工作提出了一个自主的过程来训练一个卷积神经网络（CNN）的机器人设置对象检测和姿态估计。重点在于检测放置在杂乱，严密的环境中的物体，例如具有多个物体的货架。特别是，在访问3D对象模型的过程中，物理模拟环境的几个方面。模型被放置在相对于其环境的物理现实姿势中以生成标记的合成数据集。为了进一步改善对象检测，网络对使用鲁棒多视图姿态估计过程标记的真实图像进行自我训练。所提出的训练过程在几个现有的数据集上进行评估，并且使用Motoman机器人手臂对本文收集的数据集进行评估。结果表明，提出的方法优于流行的训练过程依赖于综合 - 而不是物理上的现实 - 数据和手动注释。关键的贡献是在合成数据生成过程中结合了物理推理以及对实际图像的注释过程的自动化。

##### URL
[https://arxiv.org/abs/1703.03347](https://arxiv.org/abs/1703.03347)

