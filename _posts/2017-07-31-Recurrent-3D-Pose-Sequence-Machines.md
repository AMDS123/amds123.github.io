---
layout: post
title: "Recurrent 3D Pose Sequence Machines"
date: 2017-07-31 02:06:45
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction
author: Mude Lin, Liang Lin, Xiaodan Liang, Keze Wang, Hui Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
3D human articulated pose recovery from monocular image sequences is very challenging due to the diverse appearances, viewpoints, occlusions, and also the human 3D pose is inherently ambiguous from the monocular imagery. It is thus critical to exploit rich spatial and temporal long-range dependencies among body joints for accurate 3D pose sequence prediction. Existing approaches usually manually design some elaborate prior terms and human body kinematic constraints for capturing structures, which are often insufficient to exploit all intrinsic structures and not scalable for all scenarios. In contrast, this paper presents a Recurrent 3D Pose Sequence Machine(RPSM) to automatically learn the image-dependent structural constraint and sequence-dependent temporal context by using a multi-stage sequential refinement. At each stage, our RPSM is composed of three modules to predict the 3D pose sequences based on the previously learned 2D pose representations and 3D poses: (i) a 2D pose module extracting the image-dependent pose representations, (ii) a 3D pose recurrent module regressing 3D poses and (iii) a feature adaption module serving as a bridge between module (i) and (ii) to enable the representation transformation from 2D to 3D domain. These three modules are then assembled into a sequential prediction framework to refine the predicted poses with multiple recurrent stages. Extensive evaluations on the Human3.6M dataset and HumanEva-I dataset show that our RPSM outperforms all state-of-the-art approaches for 3D pose estimation.

##### Abstract (translated by Google)
从单眼图像序列的3D人类关节姿态恢复是非常具有挑战性的，由于不同的外观，视点，遮挡，并且人类3D姿态从单眼图像本身是不明确的。因此，利用身体关节之间丰富的空间和时间长程依赖性来进行准确的三维姿势序列预测是至关重要的。现有的方法通常是手动设计一些复杂的先验术语和人体运动学约束来捕捉结构，这往往不足以利用所有的内在结构，并且不能适用于所有场景。相反，本文提出了一种循环三维姿态序列机（RPSM），通过使用多阶段顺序细化来自动学习图像相关的结构约束和依赖于序列的时间背景。在每个阶段，我们的RPSM由三个模块组成，以基于先前学习的2D姿势表示和3D姿势来预测3D姿势序列：（i）提取依赖于图像的姿势表示的2D姿势模块，（ii）3D姿势（iii）用作模块（i）和（ii）之间的桥梁的特征自适应模块以使得能够将表示从2D转换到3D域。然后将这三个模块组合成一个顺序预测框架，以利用多个经常性阶段来改进预测的姿势。对Human3.6M数据集和HumanEva-I数据集的广泛评估表明，我们的RPSM优于所有用于3D姿态估计的最先进的方法。

##### URL
[https://arxiv.org/abs/1707.09695](https://arxiv.org/abs/1707.09695)

##### PDF
[https://arxiv.org/pdf/1707.09695](https://arxiv.org/pdf/1707.09695)

