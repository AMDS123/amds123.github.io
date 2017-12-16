---
layout: post
title: "3DCNN-DQN-RNN: A Deep Reinforcement Learning Framework for Semantic Parsing of Large-scale 3D Point Clouds"
date: 2017-07-21 07:28:14
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Reinforcement_Learning CNN Image_Classification RNN Classification Deep_Learning
author: Fangyu Liu, Shuaipeng Li, Liqiang Zhang, Chenghu Zhou, Rongtian Ye, Yuebin Wang, Jiwen Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic parsing of large-scale 3D point clouds is an important research topic in computer vision and remote sensing fields. Most existing approaches utilize hand-crafted features for each modality independently and combine them in a heuristic manner. They often fail to consider the consistency and complementary information among features adequately, which makes them difficult to capture high-level semantic structures. The features learned by most of the current deep learning methods can obtain high-quality image classification results. However, these methods are hard to be applied to recognize 3D point clouds due to unorganized distribution and various point density of data. In this paper, we propose a 3DCNN-DQN-RNN method which fuses the 3D convolutional neural network (CNN), Deep Q-Network (DQN) and Residual recurrent neural network (RNN) for an efficient semantic parsing of large-scale 3D point clouds. In our method, an eye window under control of the 3D CNN and DQN can localize and segment the points of the object class efficiently. The 3D CNN and Residual RNN further extract robust and discriminative features of the points in the eye window, and thus greatly enhance the parsing accuracy of large-scale point clouds. Our method provides an automatic process that maps the raw data to the classification results. It also integrates object localization, segmentation and classification into one framework. Experimental results demonstrate that the proposed method outperforms the state-of-the-art point cloud classification methods.

##### Abstract (translated by Google)
大规模三维点云的语义分析是计算机视觉和遥感领域的一个重要研究课题。大多数现有的方法独立地为每种模式使用手工制作的特征，并以启发式的方式将其组合。它们往往不能充分考虑到特征间的一致性和互补性，难以捕捉到高层次的语义结构。目前大多数深度学习方法学到的特征可以获得高质量的图像分类结果。然而，由于数据的无序分布和各种点密度，这些方法很难应用于识别三维点云。本文提出了一种融合三维卷积神经网络（CNN），深度Q网络（DQN）和残差递归神经网络（RNN）的3DCNN-DQN-RNN方法，实现了大规模三维点云。在我们的方法中，在3D CNN和DQN的控制下的眼窗可以有效地定位和分割对象类的点。 3D CNN和残差RNN进一步提取了眼图窗口中点的鲁棒性和判别性特征，大大提高了大规模点云的解析精度。我们的方法提供了一个将原始数据映射到分类结果的自动过程。它还将对象本地化，分割和分类整合到一个框架中。实验结果表明，该方法优于现有的点云分类方法。

##### URL
[https://arxiv.org/abs/1707.06783](https://arxiv.org/abs/1707.06783)

##### PDF
[https://arxiv.org/pdf/1707.06783](https://arxiv.org/pdf/1707.06783)

