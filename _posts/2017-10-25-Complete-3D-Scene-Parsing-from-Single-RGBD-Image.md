---
layout: post
title: "Complete 3D Scene Parsing from Single RGBD Image"
date: 2017-10-25 23:04:14
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Chuhang Zou, Zhizhong Li, Derek Hoiem
mathjax: true
---

* content
{:toc}

##### Abstract
Inferring the location, shape, and class of each object in a single image is an important task in computer vision. In this paper, we aim to predict the full 3D parse of both visible and occluded portions of the scene from one RGBD image. We parse the scene by modeling objects as detailed CAD models with class labels and layouts as 3D planes. Such an interpretation is useful for visual reasoning and robotics, but difficult to produce due to the high degree of occlusion and the diversity of object classes. We follow the recent approaches that retrieve shape candidates for each RGBD region proposal, transfer and align associated 3D models to compose a scene that is consistent with observations. We propose to use support inference to aid interpretation and propose a retrieval scheme that uses convolutional neural networks (CNNs) to classify regions and retrieve objects with similar shapes. We demonstrate the performance of our method compared with the state-of-the-art on our new NYUd v2 dataset annotations which are semi-automatically labelled with detailed 3D shapes for all the objects.

##### Abstract (translated by Google)
在一幅图像中推测每个对象的位置，形状和类别是计算机视觉中的一项重要任务。在本文中，我们旨在从一个RGBD图像预测场景的可见和遮挡部分的全3D解析。我们通过将对象建模为具有类标签和布局的详细CAD模型作为3D平面来解析场景。这种解释对于视觉推理和机器人学是有用的，但是由于高度的遮挡和对象类的多样性而难以产生。我们遵循最近的方法来检索每个RGBD区域提案的形状候选，传输和对齐相关联的3D模型以组成与观察一致的场景。我们建议使用支持推理来帮助解释，并提出一种使用卷积神经网络（CNN）对区域进行分类并检索具有相似形状的对象的检索方案。我们展示了我们的方法的性能，与我们新的NYUd v2数据集注释中的最新技术进行比较，这些注释半自动地标记为所有对象的详细3D形状。

##### URL
[https://arxiv.org/abs/1710.09490](https://arxiv.org/abs/1710.09490)

##### PDF
[https://arxiv.org/pdf/1710.09490](https://arxiv.org/pdf/1710.09490)

