---
layout: post
title: "Semantic Scene Completion from a Single Depth Image"
date: 2016-11-28 03:38:42
categories: arXiv_CV
tags: arXiv_CV CNN
author: Shuran Song, Fisher Yu, Andy Zeng, Angel X. Chang, Manolis Savva, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
This paper focuses on semantic scene completion, a task for producing a complete 3D voxel representation of volumetric occupancy and semantic labels for a scene from a single-view depth map observation. Previous work has considered scene completion and semantic labeling of depth maps separately. However, we observe that these two problems are tightly intertwined. To leverage the coupled nature of these two tasks, we introduce the semantic scene completion network (SSCNet), an end-to-end 3D convolutional network that takes a single depth image as input and simultaneously outputs occupancy and semantic labels for all voxels in the camera view frustum. Our network uses a dilation-based 3D context module to efficiently expand the receptive field and enable 3D context learning. To train our network, we construct SUNCG - a manually created large-scale dataset of synthetic 3D scenes with dense volumetric annotations. Our experiments demonstrate that the joint model outperforms methods addressing each task in isolation and outperforms alternative approaches on the semantic scene completion task.

##### Abstract (translated by Google)
本文着重于语义场景完成，一个任务是从一个单视图深度图观察产生一个完整的三维立体像素表示体积占用和一个场景的语义标签。以前的工作分别考虑了深度图的场景完成和语义标记。但是，我们观察到这两个问题是紧密交织在一起的。为了利用这两个任务的耦合性质，我们引入了语义场景完成网络（SSCNet），这是一个端到端的三维卷积网络，它将一个深度图像作为输入，同时输出所有体素的占用和语义标签相机视锥体。我们的网络使用基于扩张的3D上下文模块来有效地扩展接受领域并使3D情境学习成为可能。为了训练我们的网络，我们构建了SUNCG--一个手动创建的具有密集体积注释的合成3D场景的大规模数据集。我们的实验证明，联合模型胜过孤立地处理每个任务的方法，并且胜过在语义场景完成任务上的替代方法。

##### URL
[https://arxiv.org/abs/1611.08974](https://arxiv.org/abs/1611.08974)

##### PDF
[https://arxiv.org/pdf/1611.08974](https://arxiv.org/pdf/1611.08974)

