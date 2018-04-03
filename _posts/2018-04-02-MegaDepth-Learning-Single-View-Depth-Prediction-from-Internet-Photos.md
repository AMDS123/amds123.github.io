---
layout: post
title: "MegaDepth: Learning Single-View Depth Prediction from Internet Photos"
date: 2018-04-02 16:03:34
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation Deep_Learning Prediction Relation
author: Zhengqi Li, Noah Snavely
mathjax: true
---

* content
{:toc}

##### Abstract
Single-view depth prediction is a fundamental problem in computer vision. Recently, deep learning methods have led to significant progress, but such methods are limited by the available training data. Current datasets based on 3D sensors have key limitations, including indoor-only images (NYU), small numbers of training examples (Make3D), and sparse sampling (KITTI). We propose to use multi-view Internet photo collections, a virtually unlimited data source, to generate training data via modern structure-from-motion and multi-view stereo (MVS) methods, and present a large depth dataset called MegaDepth based on this idea. Data derived from MVS comes with its own challenges, including noise and unreconstructable objects. We address these challenges with new data cleaning methods, as well as automatically augmenting our data with ordinal depth relations generated using semantic segmentation. We validate the use of large amounts of Internet data by showing that models trained on MegaDepth exhibit strong generalization-not only to novel scenes, but also to other diverse datasets including Make3D, KITTI, and DIW, even when no images from those datasets are seen during training.

##### Abstract (translated by Google)
单视点深度预测是计算机视觉中的一个基本问题。最近，深度学习方法已经取得了重大进展，但这种方法受限于可用的训练数据。目前基于3D传感器的数据集存在关键局限性，包括仅有室内图像（NYU），少量训练实例（Make3D）和稀疏采样（KITTI）。我们建议使用多视图互联网照片集，一个几乎无限的数据源，通过现代运动结构和多视图立体（MVS）方法生成训练数据，并基于这个想法呈现一个名为MegaDepth的大型深度数据集。来自MVS的数据带来了自己的挑战，包括噪音和不可重构的物体。我们利用新的数据清理方法解决了这些挑战，并通过使用语义分割生成的序数深度关系自动扩充了我们的数据。我们通过展示在MegaDepth上训练的模型展示了强大的泛化，不仅对于新的场景，而且对包括Make3D，KITTI和DIW在内的其他各种数据集，即使没有看到来自这些数据集的图像，也验证了大量互联网数据的使用在训练中。

##### URL
[http://arxiv.org/abs/1804.00607](http://arxiv.org/abs/1804.00607)

##### PDF
[http://arxiv.org/pdf/1804.00607](http://arxiv.org/pdf/1804.00607)

