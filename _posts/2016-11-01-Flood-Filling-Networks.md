---
layout: post
title: "Flood-Filling Networks"
date: 2016-11-01 23:17:55
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Optimization Prediction Detection
author: Michał Januszewski, Jeremy Maitin-Shepard, Peter Li, Jörgen Kornfeld, Winfried Denk, Viren Jain
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art image segmentation algorithms generally consist of at least two successive and distinct computations: a boundary detection process that uses local image information to classify image locations as boundaries between objects, followed by a pixel grouping step such as watershed or connected components that clusters pixels into segments. Prior work has varied the complexity and approach employed in these two steps, including the incorporation of multi-layer neural networks to perform boundary prediction, and the use of global optimizations during pixel clustering. We propose a unified and end-to-end trainable machine learning approach, flood-filling networks, in which a recurrent 3d convolutional network directly produces individual segments from a raw image. The proposed approach robustly segments images with an unknown and variable number of objects as well as highly variable object sizes. We demonstrate the approach on a challenging 3d image segmentation task, connectomic reconstruction from volume electron microscopy data, on which flood-filling neural networks substantially improve accuracy over other state-of-the-art methods. The proposed approach can replace complex multi-step segmentation pipelines with a single neural network that is learned end-to-end.

##### Abstract (translated by Google)
最先进的图像分割算法通常包括至少两个连续且不同的计算：边界检测处理，其使用局部图像信息来将图像位置分类为对象之间的边界，随后是像素分组步骤，诸如分水岭或连接将像素聚类为段的组件。先前的工作已经改变了在这两个步骤中采用的复杂性和方法，包括结合多层神经网络来执行边界预测，以及在像素聚类期间使用全局优化。我们提出了一个统一的，端到端的可训练机器学习方法，填充网络，其中一个经常性的三维卷积网络直接从原始图像产生单独的片段。所提出的方法可靠地将图像分割成未知和可变数目的对象以及高度可变的对象大小。我们演示了一个具有挑战性的3D图像分割任务的方法，从体积电子显微镜数据的连续体重建，其中洪水填充神经网络大大提高了其他最先进的方法的准确性。所提出的方法可以用单端神经网络代替复杂的多步分割流水线。

##### URL
[https://arxiv.org/abs/1611.00421](https://arxiv.org/abs/1611.00421)

##### PDF
[https://arxiv.org/pdf/1611.00421](https://arxiv.org/pdf/1611.00421)

