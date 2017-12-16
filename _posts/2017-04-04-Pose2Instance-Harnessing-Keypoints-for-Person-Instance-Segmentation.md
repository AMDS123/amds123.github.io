---
layout: post
title: "Pose2Instance: Harnessing Keypoints for Person Instance Segmentation"
date: 2017-04-04 18:41:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Subarna Tripathi, Maxwell Collins, Matthew Brown, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
Human keypoints are a well-studied representation of people.We explore how to use keypoint models to improve instance-level person segmentation. The main idea is to harness the notion of a distance transform of oracle provided keypoints or estimated keypoint heatmaps as a prior for person instance segmentation task within a deep neural network. For training and evaluation, we consider all those images from COCO where both instance segmentation and human keypoints annotations are available. We first show how oracle keypoints can boost the performance of existing human segmentation model during inference without any training. Next, we propose a framework to directly learn a deep instance segmentation model conditioned on human pose. Experimental results show that at various Intersection Over Union (IOU) thresholds, in a constrained environment with oracle keypoints, the instance segmentation accuracy achieves 10% to 12% relative improvements over a strong baseline of oracle bounding boxes. In a more realistic environment, without the oracle keypoints, the proposed deep person instance segmentation model conditioned on human pose achieves 3.8% to 10.5% relative improvements comparing with its strongest baseline of a deep network trained only for segmentation.

##### Abstract (translated by Google)
人的关键点是对人的充分研究的表示。我们探讨如何使用关键点模型来改善实例级的人分割。主要思想是利用oracle提供的关键点或估计的关键点热图的距离变换的概念作为深度神经网络中的人实例分割任务的先验。对于训练和评估，我们考虑来自COCO的所有那些实例分段和人工关键点注释都可用的图像。我们首先展示了在没有任何训练的情况下，oracle关键点如何能够在推理期间提升现有的人类细分模型的性能接下来，我们提出了一个框架，直接学习一个深刻的实例分割模型的人的姿势。实验结果表明，在各种交叉口（IOU）阈值下，在一个带有关键点约束的约束环境下，实例分割的准确率相对于一个强大的oracle边界框基线可以达到10％〜12％的相对改进。在一个更现实的环境中，没有oracle关键点，所提出的以人为姿态为条件的深度人实例分割模型，与仅为分割训练的深度网络最强基线相比，实现了3.8％至10.5％的相对改进。

##### URL
[https://arxiv.org/abs/1704.01152](https://arxiv.org/abs/1704.01152)

##### PDF
[https://arxiv.org/pdf/1704.01152](https://arxiv.org/pdf/1704.01152)

