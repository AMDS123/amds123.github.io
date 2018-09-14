---
layout: post
title: "Canonical and Compact Point Cloud Representation for Shape Classification"
date: 2018-09-13 08:11:18
categories: arXiv_CV
tags: arXiv_CV Classification
author: Kent Fujiwara, Ikuro Sato, Mitsuru Ambai, Yuichi Yoshida, Yoshiaki Sakakura
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel compact point cloud representation that is inherently invariant to scale, coordinate change and point permutation. The key idea is to parametrize a distance field around an individual shape into a unique, canonical, and compact vector in an unsupervised manner. We firstly project a distance field to a $4$D canonical space using singular value decomposition. We then train a neural network for each instance to non-linearly embed its distance field into network parameters. We employ a bias-free Extreme Learning Machine (ELM) with ReLU activation units, which has scale-factor commutative property between layers. We demonstrate the descriptiveness of the instance-wise, shape-embedded network parameters by using them to classify shapes in $3$D datasets. Our learning-based representation requires minimal augmentation and simple neural networks, where previous approaches demand numerous representations to handle coordinate change and point permutation.

##### Abstract (translated by Google)
我们提出了一种新颖的紧凑点云表示，其具有固有的比例，坐标变化和点置换的不变性。关键思想是以无人监督的方式将单个形状周围的距离场参数化为唯一的，规范的和紧凑的矢量。我们首先使用奇异值分解将距离场投影到$ 4 $ D规范空间。然后，我们为每个实例训练一个神经网络，将其距离场非线性地嵌入到网络参数中。我们采用具有ReLU激活单元的无偏差极限学习机（ELM），其具有层之间的比例因子可交换属性。我们通过使用它们对$ 3 $ D数据集中的形状进行分类来演示实例式，形状嵌入式网络参数的描述性。我们基于学习的表示需要最小的增强和简单的神经网络，其中先前的方法需要许多表示来处理坐标变化和点置换。

##### URL
[http://arxiv.org/abs/1809.04820](http://arxiv.org/abs/1809.04820)

##### PDF
[http://arxiv.org/pdf/1809.04820](http://arxiv.org/pdf/1809.04820)

