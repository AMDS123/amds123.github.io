---
layout: post
title: "MODNet: Moving Object Detection Network with Motion and Appearance for Autonomous Driving"
date: 2017-11-12 18:20:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Mennatullah Siam, Heba Mahgoub, Mohamed Zahran, Senthil Yogamani, Martin Jagersand, Ahmad El-Sallab
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel multi-task learning system that combines appearance and motion cues for a better semantic reasoning of the environment. A unified architecture for joint vehicle detection and motion segmentation is introduced. In this architecture, a two-stream encoder is shared among both tasks. In order to evaluate our method in autonomous driving setting, KITTI annotated sequences with detection and odometry ground truth are used to automatically generate static/dynamic annotations on the vehicles. This dataset is called KITTI Moving Object Detection dataset (KITTI MOD). The dataset will be made publicly available to act as a benchmark for the motion detection task. Our experiments show that the proposed method outperforms state of the art methods that utilize motion cue only with 21.5% in mAP on KITTI MOD. Our method performs on par with the state of the art unsupervised methods on DAVIS benchmark for generic object segmentation. One of our interesting conclusions is that joint training of motion segmentation and vehicle detection benefits motion segmentation. Motion segmentation has relatively fewer data, unlike the detection task. However, the shared fusion encoder benefits from joint training to learn a generalized representation. The proposed method runs in 120 ms per frame, which beats the state of the art motion detection/segmentation in computational efficiency.

##### Abstract (translated by Google)
我们提出了一个新的多任务学习系统，它结合了外观和运动线索，以便更好地对环境进行语义推理。介绍了联合车辆检测和运动分割的统一架构。在这个架构中，两个任务之间共享一个双流编码器。为了评估我们在自动驾驶设置中的方法，KITTI带有检测和测距地面真值的注释序列被用于在车辆上自动生成静态/动态注释。这个数据集被称为KITTI移动对象检测数据集（KITTI MOD）。数据集将公开可用作运动检测任务的基准。我们的实验表明，所提出的方法优于现有技术方法，在KITTI MOD上仅利用mAP中的运动提示21.5％。我们的方法与通用对象分割的DAVIS基准测试的先进的无监督方法相媲美。我们有趣的结论之一是运动分割和车辆检测的联合训练有益于运动分割。与检测任务不同，运动分割具有相对较少的数据。然而，共享的融合编码器从联合训练中获益以学习广义表示。所提出的方法以每帧120ms运行，这在计算效率上击败了现有技术的运动检测/分割的状态。

##### URL
[https://arxiv.org/abs/1709.04821](https://arxiv.org/abs/1709.04821)

