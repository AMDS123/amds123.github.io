---
layout: post
title: "MoCap-guided Data Augmentation for 3D Pose Estimation in the Wild"
date: 2016-10-28 12:43:51
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Classification
author: Grégory Rogez, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of 3D human pose estimation in the wild. A significant challenge is the lack of training data, i.e., 2D images of humans annotated with 3D poses. Such data is necessary to train state-of-the-art CNN architectures. Here, we propose a solution to generate a large set of photorealistic synthetic images of humans with 3D pose annotations. We introduce an image-based synthesis engine that artificially augments a dataset of real images with 2D human pose annotations using 3D Motion Capture (MoCap) data. Given a candidate 3D pose our algorithm selects for each joint an image whose 2D pose locally matches the projected 3D pose. The selected images are then combined to generate a new synthetic image by stitching local image patches in a kinematically constrained manner. The resulting images are used to train an end-to-end CNN for full-body 3D pose estimation. We cluster the training data into a large number of pose classes and tackle pose estimation as a K-way classification problem. Such an approach is viable only with large training sets such as ours. Our method outperforms the state of the art in terms of 3D pose estimation in controlled environments (Human3.6M) and shows promising results for in-the-wild images (LSP). This demonstrates that CNNs trained on artificial images generalize well to real images.

##### Abstract (translated by Google)
本文针对野外三维人体姿态估计问题。一个重大的挑战是缺乏训练数据，即用3D姿势注释的人的2D图像。这些数据对于培训最先进的CNN体​​系结构是必要的。在这里，我们提出了一个解决方案来生成一个3D人脸注释人类大量的真实感合成图像。我们介绍一种基于图像的综合引擎，它使用3D运动捕捉（MoCap）数据，用2D人体姿态注释人为地增强真实图像的数据集。给定候选3D姿态，我们的算法为每个关节选择2D姿态局部匹配投影3D姿态的图像。然后将所选择的图像组合以通过以运动学约束的方式缝合局部图像块来生成新的合成图像。所得到的图像被用于训练全身3D姿态估计的端到端CNN。我们将训练数据聚类到大量的姿态类中，并将姿态估计作为K路分类问题来处理。只有像我们这样的大型训练集，这种方法才是可行的。我们的方法在受控环境（Human3.6M）中的三维姿态估计方面优于现有技术，并且在野外图像（LSP）中显示出有希望的结果。这表明CNN在人造图像上进行训练可以很好地展示真实的图像。

##### URL
[https://arxiv.org/abs/1607.02046](https://arxiv.org/abs/1607.02046)

##### PDF
[https://arxiv.org/pdf/1607.02046](https://arxiv.org/pdf/1607.02046)

