---
layout: post
title: "Discovery of Latent 3D Keypoints via End-to-end Geometric Reasoning"
date: 2018-07-05 17:41:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection
author: Supasorn Suwajanakorn, Noah Snavely, Jonathan Tompson, Mohammad Norouzi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents KeypointNet, an end-to-end geometric reasoning framework to learn an optimal set of category-specific 3D keypoints, along with their detectors. Given a single image, KeypointNet extracts 3D keypoints that are optimized for a downstream task. We demonstrate this framework on 3D pose estimation by proposing a differentiable objective that seeks the optimal set of keypoints for recovering the relative pose between two views of an object. Our model discovers geometrically and semantically consistent keypoints across viewing angles and instances of an object category. Importantly, we find that our end-to-end framework using no ground-truth keypoint annotations outperforms a fully supervised baseline using the same neural network architecture on the task of pose estimation. The discovered 3D keypoints on the car, chair, and plane categories of ShapeNet are visualized at <a href="http://keypointnet.github.io/.">this http URL</a>

##### Abstract (translated by Google)
本文介绍了KeypointNet，这是一个端到端的几何推理框架，用于学习一组最佳的类别3D关键点及其探测器。给定单个图像，KeypointNet提取针对下游任务优化的3D关键点。我们通过提出一个可微分的目标来展示这个关于3D姿态估计的框架，该目标寻求用于恢复对象的两个视图之间的相对姿势的最佳关键点集。我们的模型发现跨视角和对象类实例的几何和语义一致的关键点。重要的是，我们发现不使用地面实况关键点注释的端到端框架在姿态估计任务中使用相同的神经网络架构优于完全监督的基线。通过<a href="http://keypointnet.github.io/.">此http URL </a>可视化在ShapeNet的汽车，座椅和飞机类别上发现的3D关键点。

##### URL
[http://arxiv.org/abs/1807.03146](http://arxiv.org/abs/1807.03146)

##### PDF
[http://arxiv.org/pdf/1807.03146](http://arxiv.org/pdf/1807.03146)

