---
layout: post
title: "S3Pool: Pooling with Stochastic Spatial Sampling"
date: 2016-11-16 04:17:52
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Shuangfei Zhai, Hui Wu, Abhishek Kumar, Yu Cheng, Yongxi Lu, Zhongfei Zhang, Rogerio Feris
mathjax: true
---

* content
{:toc}

##### Abstract
Feature pooling layers (e.g., max pooling) in convolutional neural networks (CNNs) serve the dual purpose of providing increasingly abstract representations as well as yielding computational savings in subsequent convolutional layers. We view the pooling operation in CNNs as a two-step procedure: first, a pooling window (e.g., $2\times 2$) slides over the feature map with stride one which leaves the spatial resolution intact, and second, downsampling is performed by selecting one pixel from each non-overlapping pooling window in an often uniform and deterministic (e.g., top-left) manner. Our starting point in this work is the observation that this regularly spaced downsampling arising from non-overlapping windows, although intuitive from a signal processing perspective (which has the goal of signal reconstruction), is not necessarily optimal for \emph{learning} (where the goal is to generalize). We study this aspect and propose a novel pooling strategy with stochastic spatial sampling (S3Pool), where the regular downsampling is replaced by a more general stochastic version. We observe that this general stochasticity acts as a strong regularizer, and can also be seen as doing implicit data augmentation by introducing distortions in the feature maps. We further introduce a mechanism to control the amount of distortion to suit different datasets and architectures. To demonstrate the effectiveness of the proposed approach, we perform extensive experiments on several popular image classification benchmarks, observing excellent improvements over baseline models. Experimental code is available at this https URL

##### Abstract (translated by Google)
卷积神经网络（CNN）中的特征合并层（例如，最大合并）服务于提供越来越抽象的表示以及在随后的卷积层中产生计算节省的双重目的。我们将CNN中的联合操作视为一个两步过程：首先，共享窗口（例如，$ 2 \ times 2 $）在特征映射上滑动，并跨越空间分辨率的完整性;第二，下采样由以通常均匀且确定的（例如，左上）方式从每个非重叠池窗口中选择一个像素。我们在这项工作中的出发点是这样的观察，即从信号处理的角度（其具有信号重构的目的）直观地看来，由非重叠窗引起的这种规则间隔的下采样对于\ emph {学习}不一定是最佳的目标是推广）。我们研究这个方面，并提出了一种随机空间抽样（S3Pool）的新型汇集策略，其中常规的下采样被更一般的随机版本取代。我们观察到，这种普遍的随机性作为一个强大的正规化者，也可以被看作是通过在特征映射中引入失真来进行隐式数据增强。我们进一步引入一个机制来控制失真的数量，以适应​​不同的数据集和体系结构。为了证明所提出的方法的有效性，我们在几个流行的图像分类基准上进行了广泛的实验，观察到比基线模型更好的改进。这个https网址提供了实验性代码

##### URL
[https://arxiv.org/abs/1611.05138](https://arxiv.org/abs/1611.05138)

##### PDF
[https://arxiv.org/pdf/1611.05138](https://arxiv.org/pdf/1611.05138)

