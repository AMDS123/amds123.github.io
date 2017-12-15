---
layout: post
title: "Recombinator Networks: Learning Coarse-to-Fine Feature Aggregation"
date: 2016-04-17 23:29:25
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Image_Classification Classification Prediction
author: Sina Honari, Jason Yosinski, Pascal Vincent, Christopher Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks with alternating convolutional, max-pooling and decimation layers are widely used in state of the art architectures for computer vision. Max-pooling purposefully discards precise spatial information in order to create features that are more robust, and typically organized as lower resolution spatial feature maps. On some tasks, such as whole-image classification, max-pooling derived features are well suited; however, for tasks requiring precise localization, such as pixel level prediction and segmentation, max-pooling destroys exactly the information required to perform well. Precise localization may be preserved by shallow convnets without pooling but at the expense of robustness. Can we have our max-pooled multi-layered cake and eat it too? Several papers have proposed summation and concatenation based methods for combining upsampled coarse, abstract features with finer features to produce robust pixel level predictions. Here we introduce another model --- dubbed Recombinator Networks --- where coarse features inform finer features early in their formation such that finer features can make use of several layers of computation in deciding how to use coarse features. The model is trained once, end-to-end and performs better than summation-based architectures, reducing the error from the previous state of the art on two facial keypoint datasets, AFW and AFLW, by 30\% and beating the current state-of-the-art on 300W without using extra data. We improve performance even further by adding a denoising prediction model based on a novel convnet formulation.

##### Abstract (translated by Google)
具有交替卷积，最大池和抽取层的深度神经网络被广泛用于计算机视觉的现有技术架构中。最大集中有目的地丢弃精确的空间信息，以创建更强大的功能，通常组织为较低分辨率的空间特征地图。在一些任务，如全图分类，最大池导出的功能是非常适合的;然而，对于需要精确定位的任务，如像素级别的预测和分割，最大池化会严重破坏执行良好所需的信息。精确的定位可以通过浅的小圆点来保存，而不会导致汇集，但是以牺牲鲁棒性为代价。我们可以有我们最大的多层蛋糕吃吗？几篇论文提出了基于求和和连接的方法，用于将上采样粗略的抽象特征与更精细的特征组合以生成鲁棒的像素级预测。在这里，我们介绍另一个模型 - 称为重组器网络---其中粗糙的特征在其形成早期通知更精细的特征，使得更精细的特征可以利用多层计算来决定如何使用粗糙特征。该模型经过一次端对端的训练，性能优于基于总和的体系结构，将两个面部关键点数据集（AFW和AFLW）的先前状态的误差减少了30％，并击败了当前的状态 - 无需使用额外的数据，即可实现300W的最新技术。我们进一步提高性能，增加一个基于新颖的convnet公式的去噪预测模型。

##### URL
[https://arxiv.org/abs/1511.07356](https://arxiv.org/abs/1511.07356)

##### PDF
[https://arxiv.org/pdf/1511.07356](https://arxiv.org/pdf/1511.07356)

