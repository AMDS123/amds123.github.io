---
layout: post
title: "PCL: Proposal Cluster Learning for Weakly Supervised Object Detection"
date: 2018-07-09 18:59:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised CNN Image_Classification Classification Detection Recognition
author: Peng Tang, Xinggang Wang, Song Bai, Wei Shen, Xiang Bai, Wenyu Liu, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly Supervised Object Detection (WSOD), using only image-level annotations to train object detectors, is of growing importance in object recognition. In this paper, we propose a novel end-to-end deep network for WSOD. Unlike previous networks that transfer the object detection problem to an image classification problem using Multiple Instance Learning (MIL), our strategy generates proposal clusters to learn refined instance classifiers by an iterative process. The proposals in the same cluster are spatially adjacent and associated with the same object. This prevents the network from concentrating too much on parts of objects instead of whole objects. We first show that instances can be assigned object or background labels directly based on proposal clusters for instance classifier refinement, and then show that treating each cluster as a small new bag yields fewer ambiguities than the directly assigning label method. The iterative instance classifier refinement is implemented online using multiple streams in convolutional neural networks, where the first is an MIL network and the others are for instance classifier refinement supervised by the preceding one. Experiments are conducted on the PASCAL VOC and ImageNet detection benchmarks for WSOD. Results show that our method outperforms the previous state of the art significantly.

##### Abstract (translated by Google)
仅使用图像级注释来训练物体检测器的弱监督物体检测（WSOD）在物体识别中变得越来越重要。在本文中，我们为WSOD提出了一种新颖的端到端深度网络。与使用多实例学习（MIL）将对象检测问题转移到图像分类问题的先前网络不同，我们的策略生成提议集群以通过迭代过程学习精炼的实例分类器。同一群集中的提议在空间上相邻并与同一对象相关联。这可以防止网络过度集中于对象的部分而不是整个对象。我们首先展示实例可以直接基于提案集群分配对象或背景标签，例如分类器细化，然后显示将每个集群视为一个小的新包，产生的歧义比直接分配标签方法更少。迭代实例分类器细化在卷积神经网络中使用多个流在线实现，其中第一个是MIL网络，而其他是例如由前一个监督的分类器细化。在用于WSOD的PASCAL VOC和ImageNet检测基准上进行实验。结果表明，我们的方法显着优于以前的技术水平。

##### URL
[http://arxiv.org/abs/1807.03342](http://arxiv.org/abs/1807.03342)

##### PDF
[http://arxiv.org/pdf/1807.03342](http://arxiv.org/pdf/1807.03342)

