---
layout: post
title: "Tube Convolutional Neural Network for Action Detection in Videos"
date: 2017-08-02 04:52:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Deep_Learning Detection Recognition
author: Rui Hou, Chen Chen, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has been demonstrated to achieve excellent results for image classification and object detection. However, the impact of deep learning on video analysis (e.g. action detection and recognition) has been limited due to complexity of video data and lack of annotations. Previous convolutional neural networks (CNN) based video action detection approaches usually consist of two major steps: frame-level action proposal detection and association of proposals across frames. Also, these methods employ two-stream CNN framework to handle spatial and temporal feature separately. In this paper, we propose an end-to-end deep network called Tube Convolutional Neural Network (T-CNN) for action detection in videos. The proposed architecture is a unified network that is able to recognize and localize action based on 3D convolution features. A video is first divided into equal length clips and for each clip a set of tube proposals are generated next based on 3D Convolutional Network (ConvNet) features. Finally, the tube proposals of different clips are linked together employing network flow and spatio-temporal action detection is performed using these linked video proposals. Extensive experiments on several video datasets demonstrate the superior performance of T-CNN for classifying and localizing actions in both trimmed and untrimmed videos compared to state-of-the-arts.

##### Abstract (translated by Google)
深度学习已被证明能够在图像分类和对象检测方面取得优异的结果。然而，由于视频数据的复杂性和缺少注释，深度学习对视频分析（例如，动作检测和识别）的影响受到限制。先前的基于卷积神经网络（CNN）的视频动作检测方法通常包括两个主要步骤：帧级动作提议检测和跨帧提议的关联。而且，这些方法采用双流CNN框架来分别处理空间和时间特征。在本文中，我们提出了一个称为管道卷积神经网络（T-CNN）的端到端深度网络，用于视频中的动作检测。提出的架构是一个统一的网络，能够识别和本地化基于三维卷积功能的行动。首先将视频分成等长的剪辑，然后基于三维卷积网络（ConvNet）特征为每个剪辑生成一组管提议。最后，利用网络流将不同剪辑的管提议链接在一起，并使用这些链接的视频提议来执行时空动作检测。对多个视频数据集的大量实验表明，与现有技术相比，T-CNN在修剪和未修剪的视频中对动作进行分类和定位的性能优越。

##### URL
[https://arxiv.org/abs/1703.10664](https://arxiv.org/abs/1703.10664)

##### PDF
[https://arxiv.org/pdf/1703.10664](https://arxiv.org/pdf/1703.10664)

