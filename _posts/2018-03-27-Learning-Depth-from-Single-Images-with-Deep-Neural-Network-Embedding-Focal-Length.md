---
layout: post
title: "Learning Depth from Single Images with Deep Neural Network Embedding Focal Length"
date: 2018-03-27 12:26:15
categories: arXiv_CV
tags: arXiv_CV Attention Embedding CNN Inference
author: Lei He, Guanghui Wang, Zhanyi Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Learning depth from a single image, as an important issue in scene understanding, has attracted a lot of attention in the past decade. The accuracy of the depth estimation has been improved from conditional Markov random fields, non-parametric methods, to deep convolutional neural networks most recently. However, there exist inherent ambiguities in recovering 3D from a single 2D image. In this paper, we first prove the ambiguity between the focal length and monocular depth learning, and verify the result using experiments, showing that the focal length has a great influence on accurate depth recovery. In order to learn monocular depth by embedding the focal length, we propose a method to generate synthetic varying-focal-length dataset from fixed-focal-length datasets, and a simple and effective method is implemented to fill the holes in the newly generated images. For the sake of accurate depth recovery, we propose a novel deep neural network to infer depth through effectively fusing the middle-level information on the fixed-focal-length dataset, which outperforms the state-of-the-art methods built on pre-trained VGG. Furthermore, the newly generated varying-focal-length dataset is taken as input to the proposed network in both learning and inference phases. Extensive experiments on the fixed- and varying-focal-length datasets demonstrate that the learned monocular depth with embedded focal length is significantly improved compared to that without embedding the focal length information.

##### Abstract (translated by Google)
作为场景理解中的一个重要问题，从单幅图像学习深度已经在过去十年中引起了很多关注。深度估计的准确性已从条件马尔可夫随机场，非参数方法，最近改进为深度卷积神经网络。然而，在从单个2D图像恢复3D时存在固有的模糊性。在本文中，我们首先证明了焦距与单眼深度学习之间的模糊性，并通过实验验证了结果，表明焦距对精确深度恢复有很大影响。为了通过嵌入焦距来学习单眼深度，我们提出了一种从固定焦距数据集生成合成变焦距数据集的方法，并且实现了一种简单而有效的方法来填充新生成的图像中的空洞。为了准确深度恢复，我们提出了一种新的深度神经网络，通过有效融合固定焦距数据集中的中间层信息来推断深度，这种信息优于基于预定义深度信息的先进方法，训练有素的VGG。此外，新近生成的变焦距数据集作为输入提出的网络在学习和推理阶段。在固定焦距和变焦距数据集上进行的大量实验表明，与未嵌入焦距信息相比，嵌入焦距的学习单眼深度显着提高。

##### URL
[https://arxiv.org/abs/1803.10039](https://arxiv.org/abs/1803.10039)

##### PDF
[https://arxiv.org/pdf/1803.10039](https://arxiv.org/pdf/1803.10039)

