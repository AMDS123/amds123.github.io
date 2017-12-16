---
layout: post
title: "LabelFusion: A Pipeline for Generating Ground Truth Labels for Real RGBD Data of Cluttered Scenes"
date: 2017-09-26 15:16:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Pose_Estimation
author: Pat Marion, Peter R. Florence, Lucas Manuelli, Russ Tedrake
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network (DNN) architectures have been shown to outperform traditional pipelines for object segmentation and pose estimation using RGBD data, but the performance of these DNN pipelines is directly tied to how representative the training data is of the true data. Hence a key requirement for employing these methods in practice is to have a large set of labeled data for your specific robotic manipulation task, a requirement that is not generally satisfied by existing datasets. In this paper we develop a pipeline to rapidly generate high quality RGBD data with pixelwise labels and object poses. We use an RGBD camera to collect video of a scene from multiple viewpoints and leverage existing reconstruction techniques to produce a 3D dense reconstruction. We label the 3D reconstruction using a human assisted ICP-fitting of object meshes. By reprojecting the results of labeling the 3D scene we can produce labels for each RGBD image of the scene. This pipeline enabled us to collect over 1,000,000 labeled object instances in just a few days. We use this dataset to answer questions related to how much training data is required, and of what quality the data must be, to achieve high performance from a DNN architecture.

##### Abstract (translated by Google)
深度神经网络（DNN）架构已经被证明优于传统的管道，使用RGBD数据进行物体分割和姿态估计，但是这些DNN管道的性能与训练数据对真实数据的代表性直接相关。因此，在实践中采用这些方法的一个关键要求是为您的特定机器人操作任务提供大量的标记数据，这是现有数据集通常不能满足的要求。在本文中，我们开发了一个流水线来快速生成具有像素标签和对象姿势的高质量RGBD数据。我们使用RGBD相机从多个视点收集场景的视频，并利用现有的重建技术产生3D密集重建。我们使用对象网格的人体辅助ICP拟合来标记3D重建。通过重新映射标注3D场景的结果，我们可以为场景的每个RGBD图像生成标签。这条管道使我们能够在几天内收集超过1,000,000个标记的对象实例。我们使用这个数据集来回答与需要多少训练数据有关的问题以及数据必须达到什么质量的问题，以便从DNN体系结构实现高性能。

##### URL
[https://arxiv.org/abs/1707.04796](https://arxiv.org/abs/1707.04796)

##### PDF
[https://arxiv.org/pdf/1707.04796](https://arxiv.org/pdf/1707.04796)

