---
layout: post
title: "Fully-Convolutional Point Networks for Large-Scale Point Clouds"
date: 2018-08-21 10:58:57
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Caption CNN Prediction Relation
author: Dario Rethage, Johanna Wald, J&#xfc;rgen Sturm, Nassir Navab, Federico Tombari
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposes a general-purpose, fully-convolutional network architecture for efficiently processing large-scale 3D data. One striking characteristic of our approach is its ability to process unorganized 3D representations such as point clouds as input, then transforming them internally to ordered structures to be processed via 3D convolutions. In contrast to conventional approaches that maintain either unorganized or organized representations, from input to output, our approach has the advantage of operating on memory efficient input data representations while at the same time exploiting the natural structure of convolutional operations to avoid the redundant computing and storing of spatial information in the network. The network eliminates the need to pre- or post process the raw sensor data. This, together with the fully-convolutional nature of the network, makes it an end-to-end method able to process point clouds of huge spaces or even entire rooms with up to 200k points at once. Another advantage is that our network can produce either an ordered output or map predictions directly onto the input cloud, thus making it suitable as a general-purpose point cloud descriptor applicable to many 3D tasks. We demonstrate our network's ability to effectively learn both low-level features as well as complex compositional relationships by evaluating it on benchmark datasets for semantic voxel segmentation, semantic part segmentation and 3D scene captioning.

##### Abstract (translated by Google)
这项工作提出了一种通用的，完全卷积的网络架构，用于有效处理大规模3D数据。我们的方法的一个显着特征是它能够处理无组织的3D表示，例如点云作为输入，然后将它们内部转换为有序结构，以通过3D卷积进行处理。与从输入到输出维持无组织或有组织表示的传统方法相比，我们的方法具有操作存储器有效输入数据表示的优点，同时利用卷积操作的自然结构来避免冗余计算和存储网络中的空间信息。该网络消除了对原始传感器数据进行预处理或后处理的需要。这与网络的完全卷积性质一起使其成为一种端到端的方法，能够同时处理大量空间甚至整个房间的点云，最多可达200​​k点。另一个优点是我们的网络可以直接在输入云上生成有序输出或地图预测，从而使其适合作为适用于许多3D任务的通用点云描述符。我们通过在基准数据集上对语义体素分割，语义部分分割和3D场景字幕进行评估，展示了我们网络有效学习低级特征以及复杂构图关系的能力。

##### URL
[http://arxiv.org/abs/1808.06840](http://arxiv.org/abs/1808.06840)

##### PDF
[http://arxiv.org/pdf/1808.06840](http://arxiv.org/pdf/1808.06840)

