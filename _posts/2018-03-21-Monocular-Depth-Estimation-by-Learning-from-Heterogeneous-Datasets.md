---
layout: post
title: "Monocular Depth Estimation by Learning from Heterogeneous Datasets"
date: 2018-03-21 17:18:25
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Akhil Gurram, Onay Urfalioglu, Ibrahim Halfaoui, Fahd Bouzaraa, Antonio M. Lopez
mathjax: true
---

* content
{:toc}

##### Abstract
Depth estimation provides essential information to perform autonomous driving and driver assistance. Especially, Monocular Depth Estimation is interesting from a practical point of view, since using a single camera is cheaper than many other options and avoids the need for continuous calibration strategies as required by stereo-vision approaches. State-of-the-art methods for Monocular Depth Estimation are based on Convolutional Neural Networks (CNNs). A promising line of work consists of introducing additional semantic information about the traffic scene when training CNNs for depth estimation. In practice, this means that the depth data used for CNN training is complemented with images having pixel-wise semantic labels, which usually are difficult to annotate (e.g. crowded urban images). Moreover, so far it is common practice to assume that the same raw training data is associated with both types of ground truth, i.e., depth and semantic labels. The main contribution of this paper is to show that this hard constraint can be circumvented, i.e., that we can train CNNs for depth estimation by leveraging the depth and semantic information coming from heterogeneous datasets. In order to illustrate the benefits of our approach, we combine KITTI depth and Cityscapes semantic segmentation datasets, outperforming state-of-the-art results on Monocular Depth Estimation.

##### Abstract (translated by Google)
深度估算提供了执行自动驾驶和驾驶员辅助的重要信息。特别是，单眼深度估计从实际角度来看是有趣的，因为使用单个相机比许多其他选项便宜，并且避免了立体视觉方法所需的连续校准策略的需要。用于单眼深度估计的最先进方法基于卷积神经网络（CNN）。一个有前途的工作线包括在训练CNN进行深度估计时引入关于交通场景的额外语义信息。实际上，这意味着用于CNN训练的深度数据由具有像素方式语义标签的图像补充，这些标签通常难以注释（例如拥挤的城市图像）。而且，到目前为止，通常的做法是假定相同的原始训练数据与两种类型的基础事实即深度和语义标签相关联。本文的主要贡献在于表明这一硬约束可以被规避，即我们可以通过利用来自异构数据集的深度和语义信息来训练CNN进行深度估计。为了说明我们方法的好处，我们将KITTI深度和Cityscapes语义分割数据集相结合，超越了单眼深度估计的最新成果。

##### URL
[http://arxiv.org/abs/1803.08018](http://arxiv.org/abs/1803.08018)

##### PDF
[http://arxiv.org/pdf/1803.08018](http://arxiv.org/pdf/1803.08018)

