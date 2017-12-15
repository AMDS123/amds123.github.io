---
layout: post
title: "Modeling the Sequence of Brain Volumes by Local Mesh Models for Brain Decoding"
date: 2016-03-03 12:06:00
categories: arXiv_CV
tags: arXiv_CV Relation Recognition
author: Itir Onal, Mete Ozay, Eda Mizrak, Ilke Oztekin, Fatos T. Yarman Vural
mathjax: true
---

* content
{:toc}

##### Abstract
We represent the sequence of fMRI (Functional Magnetic Resonance Imaging) brain volumes recorded during a cognitive stimulus by a graph which consists of a set of local meshes. The corresponding cognitive process, encoded in the brain, is then represented by these meshes each of which is estimated assuming a linear relationship among the voxel time series in a predefined locality. First, we define the concept of locality in two neighborhood systems, namely, the spatial and functional neighborhoods. Then, we construct spatially and functionally local meshes around each voxel, called seed voxel, by connecting it either to its spatial or functional p-nearest neighbors. The mesh formed around a voxel is a directed sub-graph with a star topology, where the direction of the edges is taken towards the seed voxel at the center of the mesh. We represent the time series recorded at each seed voxel in terms of linear combination of the time series of its p-nearest neighbors in the mesh. The relationships between a seed voxel and its neighbors are represented by the edge weights of each mesh, and are estimated by solving a linear regression equation. The estimated mesh edge weights lead to a better representation of information in the brain for encoding and decoding of the cognitive tasks. We test our model on a visual object recognition and emotional memory retrieval experiments using Support Vector Machines that are trained using the mesh edge weights as features. In the experimental analysis, we observe that the edge weights of the spatial and functional meshes perform better than the state-of-the-art brain decoding models.

##### Abstract (translated by Google)
我们代表了认知刺激记录的功能磁共振成像（功能磁共振成像）脑容量的序列由一组局部网格的图形。然后用这些网格来表示在脑中编码的相应的认知过程，其中每个网格是在假定预定义的位置中的体素时间序列之间的线性关系的情况下被估计的。首先，我们定义了两个邻域系统中的局部性概念，即空间和功能邻域。然后，我们在每个体素周围构建空间和功能局部网格，称为种子体素，通过将其连接到它的空间或功能p最近的邻居。围绕体素形成的网格是具有星形拓扑结构的有向子图，其中边缘的方向朝向网格中心处的种子体素。我们用网格中其最近邻居的时间序列的线性组合表示记录在每个种子体素上的时间序列。种子体素与其邻居之间的关系由每个网格的边权重表示，并通过求解线性回归方程来估计。估计的网格边缘权重导致更好地表示大脑中用于认知任务的编码和解码的信息。我们使用支持向量机对视觉对象识别和情绪记忆检索实验进行测试，该实验使用网格边权作为特征进行训练。在实验分析中，我们观察到空间和功能网格的边权重比现有技术的脑解码模型表现得更好。

##### URL
[https://arxiv.org/abs/1603.01067](https://arxiv.org/abs/1603.01067)

##### PDF
[https://arxiv.org/pdf/1603.01067](https://arxiv.org/pdf/1603.01067)

