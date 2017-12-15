---
layout: post
title: "Stereo Matching by Training a Convolutional Neural Network to Compare Image Patches"
date: 2016-05-18 19:53:41
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Jure Žbontar, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for extracting depth information from a rectified image pair. Our approach focuses on the first stage of many stereo algorithms: the matching cost computation. We approach the problem by learning a similarity measure on small image patches using a convolutional neural network. Training is carried out in a supervised manner by constructing a binary classification data set with examples of similar and dissimilar pairs of patches. We examine two network architectures for this task: one tuned for speed, the other for accuracy. The output of the convolutional neural network is used to initialize the stereo matching cost. A series of post-processing steps follow: cross-based cost aggregation, semiglobal matching, a left-right consistency check, subpixel enhancement, a median filter, and a bilateral filter. We evaluate our method on the KITTI 2012, KITTI 2015, and Middlebury stereo data sets and show that it outperforms other approaches on all three data sets.

##### Abstract (translated by Google)
我们提出一种从整形图像对中提取深度信息的方法。我们的方法专注于许多立体声算法的第一阶段：匹配成本计算。我们通过使用卷积神经网络在小图像块上学习相似性度量来解决这个问题。通过构建具有相似和不相似补丁对的示例的二进制分类数据集，以监督的方式进行训练。我们研究了两个网络架构：一个是速度调整，另一个是准确度。卷积神经网络的输出用于初始化立体匹配成本。一系列后处理步骤如下：基于交叉的成本聚合，半全局匹配，左右一致性检查，子像素增强，中值滤波器和双边滤波器。我们在KITTI 2012，KITTI 2015和Middlebury立体声数据集上评估我们的方法，并显示它在所有三个数据集上都优于其他方法。

##### URL
[https://arxiv.org/abs/1510.05970](https://arxiv.org/abs/1510.05970)

##### PDF
[https://arxiv.org/pdf/1510.05970](https://arxiv.org/pdf/1510.05970)

