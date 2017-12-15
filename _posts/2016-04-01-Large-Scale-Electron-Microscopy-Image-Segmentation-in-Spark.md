---
layout: post
title: "Large-Scale Electron Microscopy Image Segmentation in Spark"
date: 2016-04-01 19:53:30
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Stephen M. Plaza, Stuart E. Berg
mathjax: true
---

* content
{:toc}

##### Abstract
The emerging field of connectomics aims to unlock the mysteries of the brain by understanding the connectivity between neurons. To map this connectivity, we acquire thousands of electron microscopy (EM) images with nanometer-scale resolution. After aligning these images, the resulting dataset has the potential to reveal the shapes of neurons and the synaptic connections between them. However, imaging the brain of even a tiny organism like the fruit fly yields terabytes of data. It can take years of manual effort to examine such image volumes and trace their neuronal connections. One solution is to apply image segmentation algorithms to help automate the tracing tasks. In this paper, we propose a novel strategy to apply such segmentation on very large datasets that exceed the capacity of a single machine. Our solution is robust to potential segmentation errors which could otherwise severely compromise the quality of the overall segmentation, for example those due to poor classifier generalizability or anomalies in the image dataset. We implement our algorithms in a Spark application which minimizes disk I/O, and apply them to a few large EM datasets, revealing both their effectiveness and scalability. We hope this work will encourage external contributions to EM segmentation by providing 1) a flexible plugin architecture that deploys easily on different cluster environments and 2) an in-memory representation of segmentation that could be conducive to new advances.

##### Abstract (translated by Google)
连接组学的新兴领域旨在通过了解神经元之间的连接来解开大脑的奥秘。为了绘制这种连接性，我们采集了数以千计的纳米级分辨率的电子显微镜（EM）图像。对齐这些图像后，所得到的数据集有可能揭示神经元的形状和它们之间的突触连接。但是，即使像果蝇这样的微小有机体的大脑成像也能产生数TB的数据。可能需要花费数年的时间来检查这些图像体积并追踪它们的神经连接。一种解决方案是应用图像分割算法来帮助自动执行跟踪任务。在本文中，我们提出了一种新的策略，将这种分割应用于超过单机容量的超大型数据集上。我们的解决方案对于潜在的分割错误是有效的，否则这些分割错误可能会严重影响整体分割的质量，例如由于分类器普遍性差或图像数据集中的异常造成的分割错误。我们在一个Spark应用程序中实现了我们的算法，最大限度地减少了磁盘I / O，并将它们应用于一些大的EM数据集，揭示了它们的有效性和可扩展性。我们希望这项工作将鼓励外部对EM细分的贡献，提供1）灵活的插件体系结构，可以轻松部署在不同的集群环境中; 2）可以有助于新进展的内存分割表示。

##### URL
[https://arxiv.org/abs/1604.00385](https://arxiv.org/abs/1604.00385)

##### PDF
[https://arxiv.org/pdf/1604.00385](https://arxiv.org/pdf/1604.00385)

