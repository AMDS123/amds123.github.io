---
layout: post
title: "Leveraging Pre-Trained 3D Object Detection Models For Fast Ground Truth Generation"
date: 2018-07-16 19:33:09
categories: arXiv_AI
tags: arXiv_AI Object_Detection Segmentation Detection
author: Jungwook Lee, Sean Walsh, Ali Harakeh, Steven L. Waslander
mathjax: true
---

* content
{:toc}

##### Abstract
Training 3D object detectors for autonomous driving has been limited to small datasets due to the effort required to generate annotations. Reducing both task complexity and the amount of task switching done by annotators is key to reducing the effort and time required to generate 3D bounding box annotations. This paper introduces a novel ground truth generation method that combines human supervision with pretrained neural networks to generate per-instance 3D point cloud segmentation, 3D bounding boxes, and class annotations. The annotators provide object anchor clicks which behave as a seed to generate instance segmentation results in 3D. The points belonging to each instance are then used to regress object centroids, bounding box dimensions, and object orientation. Our proposed annotation scheme requires 30x lower human annotation time. We use the KITTI 3D object detection dataset to evaluate the efficiency and the quality of our annotation scheme. We also test the the proposed scheme on previously unseen data from the Autonomoose self-driving vehicle to demonstrate generalization capabilities of the network.

##### Abstract (translated by Google)
由于生成注释所需的努力，训练用于自动驾驶的3D物体检测器仅限于小数据集。降低任务复杂度和注释器完成的任务切换量是减少生成3D边界框注释所需的工作量和时间的关键。本文介绍了一种新的地面实况生成方法，该方法将人工监督与预训练神经网络相结合，生成实例三维点云分割，三维边界框和类注释。注释器提供对象锚点击，其表现为种子以在3D中生成实例分割结果。然后，使用属于每个实例的点来回归对象质心，边界框尺寸和对象方向。我们提出的注释方案要求人类注释时间减少30倍。我们使用KITTI 3D物体检测数据集来评估注释方案的效率和质量。我们还对来自Autonomoose自动驾驶车辆的先前未见数据进行测试，以展示网络的泛化能力。

##### URL
[http://arxiv.org/abs/1807.06072](http://arxiv.org/abs/1807.06072)

##### PDF
[http://arxiv.org/pdf/1807.06072](http://arxiv.org/pdf/1807.06072)

