---
layout: post
title: "Physics-based Scene-level Reasoning for Object Pose Estimation in Clutter"
date: 2018-06-25 20:39:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Optimization Deep_Learning Detection Recognition
author: Chaitanya Mitash, Abdeslam Boularias, Kostas Bekris
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on vision-based pose estimation for multiple rigid objects placed in clutter, especially in cases involving occlusions and objects resting on each other. Progress has been achieved recently in object recognition given advancements in deep learning. Nevertheless, such tools typically require a large amount of training data and significant manual effort to label objects. This limits their applicability in robotics, where solutions must scale to a large number of objects and variety of conditions. Moreover, the combinatorial nature of the scenes that could arise from the placement of multiple objects is hard to capture in the training dataset. Thus, the learned models might not produce the desired level of precision required for tasks, such as robotic manipulation. This work proposes an autonomous process for pose estimation that spans from data generation to scene-level reasoning and lifelong self-learning. In particular, the proposed framework first generates a labeled dataset for training a Convolutional Neural Network (CNN) for object detection in clutter. These detections are used to guide a scene-level optimization process, which considers the interactions between the different objects present in the clutter to output pose estimates of high precision. Furthermore, confident estimates are used to label online real images from multiple views and re-train the process in a lifelong self-learning pipeline. Experimental results indicate that this process is quickly able to identify in cluttered scenes physically-consistent object poses that are more precise than the ones found by reasoning over individual instances of objects. Furthermore, the quality of pose estimates increases over time given the self-learning process.

##### Abstract (translated by Google)
本文重点讨论基于视觉的姿态估计方法，用于放置在杂波中的多个刚性物体，特别是在涉及遮挡和物体彼此间的情况下。鉴于深度学习方面的进步，最近在物体识别方面取得了进展。尽管如此，这些工具通常需要大量的训练数据和大量的人工努力来标记对象。这限制了它们在机器人领域的适用性，其中解决方案必须扩展到大量物体和各种条件。此外，由于放置多个对象而导致场景的组合性质很难在训练数据集中捕捉。因此，学习的模型可能不会产生任务所需的精度要求，例如机器人操作。这项工作提出了一个自动的姿势估计过程，从数据生成到场景级推理和终身自学。具体而言，所提出的框架首先生成用于训练卷积神经网络（CNN）以用于杂波中的物体检测的标记数据集。这些检测用于指导场景级优化过程，该过程考虑杂波中存在的不同物体之间的相互作用以输出高精度的姿态估计。此外，使用可靠的估计来标记来自多个视图的在线实际图像，并在终身自学流水线中重新训练该过程。实验结果表明，这个过程很快就能够在杂乱的场景中识别物理一致的物体姿态，这种物体姿态比通过对单个物体实例推理所发现的物体姿态更精确。此外，考虑到自学过程，姿态估计的质量随着时间的推移而增加。

##### URL
[http://arxiv.org/abs/1806.10457](http://arxiv.org/abs/1806.10457)

##### PDF
[http://arxiv.org/pdf/1806.10457](http://arxiv.org/pdf/1806.10457)

