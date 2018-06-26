---
layout: post
title: "FBI-Pose: Towards Bridging the Gap between 2D Images and 3D Human Poses using Forward-or-Backward Information"
date: 2018-06-25 00:35:10
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference Quantitative
author: Yulong Shi, Xiaoguang Han, Nianjuan Jiang, Kun Zhou, Kui Jia, Jiangbo Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Although significant advances have been made in the area of human poses estimation from images using deep Convolutional Neural Network (ConvNet), it remains a big challenge to perform 3D pose inference in-the-wild. This is due to the difficulty to obtain 3D pose groundtruth for outdoor environments. In this paper, we propose a novel framework to tackle this problem by exploiting the information of each bone indicating if it is forward or backward with respect to the view of the camera(we term it Forwardor-Backward Information abbreviated as FBI). Our method firstly trains a ConvNet with two branches which maps an image of a human to both the 2D joint locations and the FBI of bones. These information is further fed into a deep regression network to predict the 3D positions of joints. To support the training, we also develop an annotation user interface and labeled such FBI for around 12K in-the-wild images which are randomly selected from MPII (a public dataset of 2D pose annotation). Our experimental results on the standard benchmarks demonstrate that our approach outperforms state-of-the-art methods both qualitatively and quantitatively.

##### Abstract (translated by Google)
尽管使用深度卷积神经网络（ConvNet）从图像估计人体姿态方面取得了重大进展，但在野外进行3D姿势推断仍然是一个巨大的挑战。这是由于难以获得户外环境的三维姿势。在本文中，我们提出了一个新的框架来解决这个问题，通过利用每个骨骼的信息来指示它是相对于摄像机的视角（我们称之为Forwardor-Backward Information缩写为FBI）的前方还是后方。我们的方法首先训练带有两个分支的ConvNet，将人的图像映射到骨骼的2D关节位置和FBI。这些信息被进一步送入深度回归网络以预测关节的3D位置。为了支持培训，我们还开发了一个注释用户界面，并将这种FBI标记为从MPII（2D姿态注释的公共数据集）中随机选择的12K左右的野外图像。我们在标准基准测试中的实验结果表明，我们的方法在性能和数量上均优于最先进的方法。

##### URL
[http://arxiv.org/abs/1806.09241](http://arxiv.org/abs/1806.09241)

##### PDF
[http://arxiv.org/pdf/1806.09241](http://arxiv.org/pdf/1806.09241)

