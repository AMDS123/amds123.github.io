---
layout: post
title: "CNN-based Action Recognition and Supervised Domain Adaptation on 3D Body Skeletons via Kernel Feature Maps"
date: 2018-06-24 04:06:18
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN RNN Deep_Learning Recognition
author: Yusuf Tas, Piotr Koniusz
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning is ubiquitous across many areas areas of computer vision. It often requires large scale datasets for training before being fine-tuned on small-to-medium scale problems. Activity, or, in other words, action recognition, is one of many application areas of deep learning. While there exist many Convolutional Neural Network architectures that work with the RGB and optical flow frames, training on the time sequences of 3D body skeleton joints is often performed via recurrent networks such as LSTM. 
 In this paper, we propose a new representation which encodes sequences of 3D body skeleton joints in texture-like representations derived from mathematically rigorous kernel methods. Such a representation becomes the first layer in a standard CNN network e.g., ResNet-50, which is then used in the supervised domain adaptation pipeline to transfer information from the source to target dataset. This lets us leverage the available Kinect-based data beyond training on a single dataset and outperform simple fine-tuning on any two datasets combined in a naive manner. More specifically, in this paper we utilize the overlapping classes between datasets. We associate datapoints of the same class via so-called commonality, known from the supervised domain adaptation. We demonstrate state-of-the-art results on three publicly available benchmarks.

##### Abstract (translated by Google)
深度学习在计算机视觉的许多领域中无处不在。在对中小规模问题进行微调之前，通常需要大规模数据集进行培训。活动，换句话说，动作识别，是深度学习的许多应用领域之一。虽然存在许多用于RGB和光流帧的卷积神经网络架构，但是通常通过诸如LSTM的递归网络来执行对3D身体骨架关节的时间序列的训练。
 在本文中，我们提出了一种新的表示方法，用数学上严格的核方法导出类似纹理的表示，对三维人体骨骼关节的序列进行编码。这样的表示成为标准CNN网络中的第一层，例如ResNet-50，然后在监督域适配管线中使用ResNet-50将信息从源传送到目标数据集。这让我们可以利用基于Kinect的可用数据超越单个数据集的训练，并且可以在任何两个数据集上以简单方式进行微调。更具体地说，在本文中，我们利用数据集之间的重叠类。我们通过所谓的通用性将同一类的数据点关联起来，从监督域自适应中知道。我们在三个公开可用的基准上展示了最先进的结果。

##### URL
[http://arxiv.org/abs/1806.09078](http://arxiv.org/abs/1806.09078)

##### PDF
[http://arxiv.org/pdf/1806.09078](http://arxiv.org/pdf/1806.09078)

