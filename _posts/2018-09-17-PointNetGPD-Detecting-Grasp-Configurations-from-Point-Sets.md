---
layout: post
title: "PointNetGPD: Detecting Grasp Configurations from Point Sets"
date: 2018-09-17 15:02:52
categories: arXiv_RO
tags: arXiv_RO Sparse CNN Quantitative
author: Hongzhuo Liang, Xiaojian Ma, Shuang Li, Michael G&#xf6;rner, Song Tang, Bin Fang, Fuchun Sun, Jianwei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an end-to-end grasp evaluation model to address the challenging problem of localizing robot grasp configurations directly from the point cloud. Compared to recent grasp evaluation metrics that are based on handcrafted depth features and a convolutional neural network (CNN), our proposed PointNetGPD is light-weighted and can directly process the 3D point cloud that locates within the gripper for grasp evaluation. Taking the raw point cloud as input, our proposed grasp evaluation network can capture the complex geometric structure of the contact area between the gripper and the object even if the point cloud is very sparse. To further improve our proposed model, we generate a larger-scale grasp dataset with 350k real point cloud and grasps with the YCB object set for training. The performance of the proposed model is quantitatively measured both in simulation and on robotic hardware. Experiments on object grasping and clutter removal show that our proposed model generalizes well to novel objects and outperforms state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出了一种端到端的抓握评估模型，以解决直接从点云定位机器人抓握配置的挑战性问题。与最近基于手工深度特征和卷积神经网络（CNN）的掌握评估指标相比，我们提出的PointNetGPD是轻量级的，可以直接处理位于抓取器内的3D点云以进行抓取评估。以原始点云为输入，即使点云非常稀疏，我们提出的抓取评估网络也可以捕获抓手与物体之间接触区域的复杂几何结构。为了进一步改进我们提出的模型，我们生成了一个包含35万个实点云的更大规模的抓取数据集，并使用YCB对象集进行训练。在模拟和机器人硬件上定量测量所提出模型的性能。物体抓取和杂波去除的实验表明，我们提出的模型很好地推广了新的对象，并且优于最先进的方法。

##### URL
[http://arxiv.org/abs/1809.06267](http://arxiv.org/abs/1809.06267)

##### PDF
[http://arxiv.org/pdf/1809.06267](http://arxiv.org/pdf/1809.06267)

