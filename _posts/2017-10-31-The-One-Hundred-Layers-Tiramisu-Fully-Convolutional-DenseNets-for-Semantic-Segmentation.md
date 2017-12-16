---
layout: post
title: "The One Hundred Layers Tiramisu: Fully Convolutional DenseNets for Semantic Segmentation"
date: 2017-10-31 13:10:48
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification Prediction
author: Simon Jégou, Michal Drozdzal, David Vazquez, Adriana Romero, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art approaches for semantic image segmentation are built on Convolutional Neural Networks (CNNs). The typical segmentation architecture is composed of (a) a downsampling path responsible for extracting coarse semantic features, followed by (b) an upsampling path trained to recover the input image resolution at the output of the model and, optionally, (c) a post-processing module (e.g. Conditional Random Fields) to refine the model predictions. Recently, a new CNN architecture, Densely Connected Convolutional Networks (DenseNets), has shown excellent results on image classification tasks. The idea of DenseNets is based on the observation that if each layer is directly connected to every other layer in a feed-forward fashion then the network will be more accurate and easier to train. In this paper, we extend DenseNets to deal with the problem of semantic segmentation. We achieve state-of-the-art results on urban scene benchmark datasets such as CamVid and Gatech, without any further post-processing module nor pretraining. Moreover, due to smart construction of the model, our approach has much less parameters than currently published best entries for these datasets. Code to reproduce the experiments is available here : this https URL

##### Abstract (translated by Google)
用于语义图像分割的最先进的方法建立在卷积神经网络（CNN）上。典型的分割体系结构由下列部分组成：（a）负责提取粗略语义特征的下采样路径;（b）训练上采样路径以恢复模型输出处的输入图像分辨率;以及可选地，（c）处理模块（例如，条件随机场）来优化模型预测。最近，CNN新架构 - 密集连接卷积网络（DenseNets）在图像分类任务上表现出色。 DenseNets的思想是基于这样的观察：如果每个层都以前馈方式直接连接到其他层，则网络将更加准确和容易地被训练。在本文中，我们扩展DenseNets来处理语义分割问题。我们在CamVid和Gatech等城市场景基准数据集上获得了最先进的成果，无需任何后期处理模块或预训练。而且，由于模型的巧妙构建，我们的方法比目前公布的这些数据集的最佳条目少得多的参数。重现实验的代码可以在这里找到：这个https URL

##### URL
[https://arxiv.org/abs/1611.09326](https://arxiv.org/abs/1611.09326)

##### PDF
[https://arxiv.org/pdf/1611.09326](https://arxiv.org/pdf/1611.09326)

