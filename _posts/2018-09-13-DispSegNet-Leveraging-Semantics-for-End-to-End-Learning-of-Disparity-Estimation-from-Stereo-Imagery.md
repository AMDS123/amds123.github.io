---
layout: post
title: "DispSegNet: Leveraging Semantics for End-to-End Learning of Disparity Estimation from Stereo Imagery"
date: 2018-09-13 01:36:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding CNN Semantic_Segmentation Deep_Learning
author: Junming Zhang, Katherine A. Skinner, Ram Vasudevan, Matthew Johnson-Roberson
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown that convolutional neural networks (CNNs) can be applied successfully in disparity estimation, but these methods still suffer from errors in regions of low-texture, occlusions and reflections. Concurrently, deep learning for semantic segmentation has shown great progress in recent years. In this paper, we design a CNN architecture that combines these two tasks to improve the quality and accuracy of disparity estimation with the help of semantic segmentation. Specifically, we propose a network structure in which these two tasks are highly coupled. One key novelty of this approach is the two-stage refinement process. Initial disparity estimates are refined with an embedding learned from the semantic segmentation branch of the network. The proposed model is trained using an unsupervised approach, in which images from one half of the stereo pair are warped and compared against images from the other camera. Another key advantage of the proposed approach is that a single network is capable of outputting disparity estimates and semantic labels. These outputs are of great use in autonomous vehicle operation; with real-time constraints being key, such performance improvements increase the viability of driving applications. Experiments on KITTI and Cityscapes datasets show that our model can achieve state-of-the-art results and that leveraging embedding learned from semantic segmentation improves the performance of disparity estimation.

##### Abstract (translated by Google)
最近的工作表明，卷积神经网络（CNN）可以成功地应用于视差估计，但是这些方法仍然存在低纹理，遮挡和反射区域中的误差。同时，语义分割的深度学习近年来取得了很大进展。在本文中，我们设计了一个CNN架构，它结合了这两个任务，在语义分割的帮助下提高了视差估计的质量和准确性。具体而言，我们提出了一种网络结构，其中这两个任务是高度耦合的。这种方法的一个关键新颖性是两阶段细化过程。利用从网络的语义分段分支学习的嵌入来细化初始视差估计。使用无监督方法训练所提出的模型，其中来自立体对的一半的图像被扭曲并且与来自另一相机的图像进行比较。所提出的方法的另一个关键优点是单个网络能够输出视差估计和语义标签。这些输出在自动驾驶车辆操作中非常有用;实时约束是关键，这种性能改进增加了驱动应用程序的可行性。 KITTI和Cityscapes数据集上的实验表明，我们的模型可以实现最先进的结果，并且利用从语义分割中学到的嵌入可以提高视差估计的性能。

##### URL
[http://arxiv.org/abs/1809.04734](http://arxiv.org/abs/1809.04734)

##### PDF
[http://arxiv.org/pdf/1809.04734](http://arxiv.org/pdf/1809.04734)

