---
layout: post
title: "Image-based Synthesis for Deep 3D Human Pose Estimation"
date: 2018-02-12 17:59:47
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Classification
author: Gr&#xe9;gory Rogez, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of 3D human pose estimation in the wild. A significant challenge is the lack of training data, i.e., 2D images of humans annotated with 3D poses. Such data is necessary to train state-of-the-art CNN architectures. Here, we propose a solution to generate a large set of photorealistic synthetic images of humans with 3D pose annotations. We introduce an image-based synthesis engine that artificially augments a dataset of real images with 2D human pose annotations using 3D motion capture data. Given a candidate 3D pose, our algorithm selects for each joint an image whose 2D pose locally matches the projected 3D pose. The selected images are then combined to generate a new synthetic image by stitching local image patches in a kinematically constrained manner. The resulting images are used to train an end-to-end CNN for full-body 3D pose estimation. We cluster the training data into a large number of pose classes and tackle pose estimation as a $K$-way classification problem. Such an approach is viable only with large training sets such as ours. Our method outperforms most of the published works in terms of 3D pose estimation in controlled environments (Human3.6M) and shows promising results for real-world images (LSP). This demonstrates that CNNs trained on artificial images generalize well to real images. Compared to data generated from more classical rendering engines, our synthetic images do not require any domain adaptation or fine-tuning stage.

##### Abstract (translated by Google)
本文讨论了野外三维人体姿态估计的问题。一个重大挑战是缺乏训练数据，即用3D姿势注释的人的2D图像。这些数据对于培训最先进的CNN架构是必要的。在这里，我们提出了一个解决方案，用3D姿势注释生成一大组照片真实感合成人类图像。我们介绍一种基于图像的合成引擎，它使用3D运动捕捉数据用2D人体姿态注释人为地增强真实图像数据集。给定一个候选3D姿态，我们的算法为每个关节选择一个2D姿态局部匹配投影3D姿态的图像。然后将选定的图像组合起来，以运动学约束方式拼接局部图像斑块，以生成新的合成图像。生成的图像用于训练全身3D姿态估计的端到端CNN。我们将训练数据聚类到大量的姿势类中，并将姿势估计作为$ K $ -way分类问题来处理。这种方法只适用于像我们这样的大型训练集。我们的方法在受控环境（Human3.6M）中的三维姿态估计方面优于大多数已发表的作品，并且显示出对于真实世界图像（LSP）的有希望的结果。这表明在人造图像上训练的CNN很好地适用于真实图像。与从更经典的渲染引擎生成的数据相比，我们的合成图像不需要任何域调整或微调阶段。

##### URL
[http://arxiv.org/abs/1802.04216](http://arxiv.org/abs/1802.04216)

##### PDF
[http://arxiv.org/pdf/1802.04216](http://arxiv.org/pdf/1802.04216)

