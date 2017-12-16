---
layout: post
title: "A fully end-to-end deep learning approach for real-time simultaneous 3D reconstruction and material recognition"
date: 2017-03-14 20:23:48
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Deep_Learning Recognition
author: Cheng Zhao, Li Sun, Rustam Stolkin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of simultaneous 3D reconstruction and material recognition and segmentation. Enabling robots to recognise different materials (concrete, metal etc.) in a scene is important for many tasks, e.g. robotic interventions in nuclear decommissioning. Previous work on 3D semantic reconstruction has predominantly focused on recognition of everyday domestic objects (tables, chairs etc.), whereas previous work on material recognition has largely been confined to single 2D images without any 3D reconstruction. Meanwhile, most 3D semantic reconstruction methods rely on computationally expensive post-processing, using Fully-Connected Conditional Random Fields (CRFs), to achieve consistent segmentations. In contrast, we propose a deep learning method which performs 3D reconstruction while simultaneously recognising different types of materials and labelling them at the pixel level. Unlike previous methods, we propose a fully end-to-end approach, which does not require hand-crafted features or CRF post-processing. Instead, we use only learned features, and the CRF segmentation constraints are incorporated inside the fully end-to-end learned system. We present the results of experiments, in which we trained our system to perform real-time 3D semantic reconstruction for 23 different materials in a real-world application. The run-time performance of the system can be boosted to around 10Hz, using a conventional GPU, which is enough to achieve real-time semantic reconstruction using a 30fps RGB-D camera. To the best of our knowledge, this work is the first real-time end-to-end system for simultaneous 3D reconstruction and material recognition.

##### Abstract (translated by Google)
本文解决了同时进行三维重建和材料识别与分割的问题。使机器人识别场景中的不同材料（混凝土，金属等）对许多任务是重要的，例如，机器人干预核退役。以前关于三维语义重构的研究主要集中在对日常家庭物体（桌椅等）的识别上，而以前在材料识别方面的工作主要局限于单个二维图像而没有任何三维重建。同时，大多数三维语义重构方法依赖于计算昂贵的后处理，使用全连接条件随机场（CRF）来实现一致的分割。相反，我们提出了一种深度学习方法，该方法执行三维重建，同时识别不同类型的材料并在像素级对其进行标记。与以前的方法不同，我们提出了一个完全端到端的方法，它不需要手工特征或CRF后处理。相反，我们只使用学习功能，CRF分段约束被整合到完全端到端的学习系统中。我们展示了实验的结果，在这个实验中，我们训练了我们的系统，在实际应用中为23种不同的材料进行实时的三维语义重建。使用传统的GPU可以将系统的运行时间性能提升到10Hz左右，这足以使用30fps的RGB-D摄像机实现实时语义重建。据我们所知，这是第一个同时进行3D重建和材料识别的实时端到端系统。

##### URL
[https://arxiv.org/abs/1703.04699](https://arxiv.org/abs/1703.04699)

##### PDF
[https://arxiv.org/pdf/1703.04699](https://arxiv.org/pdf/1703.04699)

