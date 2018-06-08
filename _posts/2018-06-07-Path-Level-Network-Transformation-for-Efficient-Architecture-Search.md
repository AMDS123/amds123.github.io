---
layout: post
title: "Path-Level Network Transformation for Efficient Architecture Search"
date: 2018-06-07 12:25:05
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Image_Classification Classification
author: Han Cai, Jiacheng Yang, Weinan Zhang, Song Han, Yong Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new function-preserving transformation for efficient neural architecture search. This network transformation allows reusing previously trained networks and existing successful architectures that improves sample efficiency. We aim to address the limitation of current network transformation operations that can only perform layer-level architecture modifications, such as adding (pruning) filters or inserting (removing) a layer, which fails to change the topology of connection paths. Our proposed path-level transformation operations enable the meta-controller to modify the path topology of the given network while keeping the merits of reusing weights, and thus allow efficiently designing effective structures with complex path topologies like Inception models. We further propose a bidirectional tree-structured reinforcement learning meta-controller to explore a simple yet highly expressive tree-structured architecture space that can be viewed as a generalization of multi-branch architectures. We experimented on the image classification datasets with limited computational resources (about 200 GPU-hours), where we observed improved parameter efficiency and better test results (97.70% test accuracy on CIFAR-10 with 14.3M parameters and 74.6% top-1 accuracy on ImageNet in the mobile setting), demonstrating the effectiveness and transferability of our designed architectures.

##### Abstract (translated by Google)
我们引入了一种新的功能保留变换，用于有效的神经架构搜索。这种网络转换允许重复使用先前训练过的网络和现有的成功架构，以提高样本效率。我们旨在解决当前网络转换操作的局限性，这些操作只能执行层级体系结构修改，例如添加（修剪）过滤器或插入（移除）无法更改连接路径拓扑的层。我们提出的路径级转换操作使元控制器能够修改给定网络的路径拓扑结构，同时保持重用权重的优点，从而可以有效地设计具有复杂路径拓扑结构的有效结构，如Inception模型。我们进一步提出了一种双向树形结构强化学习元控制器，以探索一个简单但高度表达的树形结构体系结构空间，可以将其视为多分支体系结构的一般化。我们在有限的计算资源（约200 GPU小时）下对图像分类数据集进行了实验，观察到参数效率提高和测试结果更好（CIFAR-10测试精度为97.70％，参数14.3M，精度达到74.6％ ImageNet在移动设备中），展示了我们设计的架构的有效性和可移植性。

##### URL
[http://arxiv.org/abs/1806.02639](http://arxiv.org/abs/1806.02639)

##### PDF
[http://arxiv.org/pdf/1806.02639](http://arxiv.org/pdf/1806.02639)

